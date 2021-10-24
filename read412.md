# Baeldung: Spring Request Mapping

## Spring RequestMapping


###  @RequestMapping Basics


1)  @RequestMapping — by Path

``` @RequestMapping(value = "/ex/foos", method = RequestMethod.GET)
@ResponseBody
public String getFoosBySimplePath() {
    return "Get some Foos";
}
 ```

 To test out this mapping with a simple curl command, run:

curl -i http://localhost:8080/spring-rest/ex/foos



2) RequestMapping — the HTTP Method

The HTTP method parameter has no default. So, if we don't specify a value, it's going to map to any HTTP reques

``` @RequestMapping(value = "/ex/foos", method = POST)
@ResponseBody
public String postFoos() {
    return "Post some Foos";
}
```

To test the POST via a curl command:

curl -i -X POST http://localhost:8080/spring-rest/ex/foos

 ###  RequestMapping and HTTP Headers

1) RequestMapping With the headers Attribute

```@RequestMapping(value = "/ex/foos", headers = "key=val", method = GET)
@ResponseBody
public String getFoosWithHeader() {
    return "Get some Foos with Header";
}
```

To test the operation, we're going to use the curl header support:

curl -i -H "key:val" http://localhost:8080/spring-rest/ex/foos

Consumes and Produces

2) Mapping media types produced by a controller method is worth special attention.

```@RequestMapping(
  value = "/ex/foos", 
  method = GET, 
  headers = "Accept=application/json")
@ResponseBody
public String getFoosAsJsonFromBrowser() {
    return "Get some Foos with Header Old";
}
```

### RequestMapping With Path Variables
1) Single @PathVariable

Syntax:

```@RequestMapping(value = "/ex/foos/{id}", method = GET)
@ResponseBody
public String getFoosBySimplePathWithPathVariable(
  @PathVariable("id") long id) {
    return "Get a specific Foo with id=" + id;
}
```

This can be tested with curl:

curl http://localhost:8080/spring-rest/ex/foos/1

2) Multiple @PathVariable

Syntax:

```@RequestMapping(value = "/ex/foos/{fooid}/bar/{barid}", method = GET)
@ResponseBody
public String getFoosBySimplePathWithPathVariables
  (@PathVariable long fooid, @PathVariable long barid) {
    return "Get a specific Bar with id=" + barid + 
      " from a Foo with id=" + fooid;
      }
```

This is easily tested with a curl in the same way:

curl http://localhost:8080/spring-rest/ex/foos/1/bar/2

## Accessing Data with JPA

all the guides in this referance [Link](https://spring.io/guides/gs/accessing-data-jpa/) 

 ## JpaRepository, and PagingAndSortingRepository in Spring Data

 1) JpaRepository is JPA specific extension of Repository,So it contains API for basic CRUD operations and also API for pagination and sorting.

 2) PagingAndSortingRepository
When using Pageable we created a Pageable object with certain properties and we have to specify at least

- Page size
- Current page number
- Sorting


What is the difference between CrudRepository and JpaRepository in spring boot?

CrudRepository mainly provides CRUD functions.
PagingAndSortingRepository provides methods to do pagination and sorting records.
JpaRepository provides some JPA-related methods such as flushing the persistence context and deleting records in a batch.
