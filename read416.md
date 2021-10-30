 # Spring Authentication

 
 ### authentication Vs authorization.

Authentication : means Who are you is the process of knowing the identity of the user(access control)

Authorization : means What are you allowed, allowed to access or do in the web application.


### Authentication

The application needs to verify if the user is who he/she claims to be, typically done with a username and password check.

For Authentication in spring we use the AuthenticationManager interface which has only one method:

 authenticate  can be used to do 3 main things:

- Return an Authentication 

- Throw an AuthenticationException if the input represents an invalid principle.

- Return null if it can’t decide.

```
public interface AuthenticationManager {

  Authentication authenticate(Authentication authentication)
    throws AuthenticationException;
}
```


### Customizing Authentication Managers

Spring security provides a lot of configuration helpers to quickly and flexibly get the job done.

The most commonly used helper is AuthenticationMangerBuilder, the following example shows an application that configures the parent AuthenticationManager


```
@Configuration
public class ApplicationSecurity extends WebSecurityConfigurerAdapter {

   ... // web stuff here

  @Autowired
  public void initialize(AuthenticationManagerBuilder builder, DataSource dataSource) {
    builder.jdbcAuthentication().dataSource(dataSource).withUser("OSAID920")
      .password("1234").roles("USER");
  }

}
```

### Web Security
The web Security in Spring is based on Sevlet Filters. It consists of several layers, each layer has a certain function when receiving a single HTTP request. For example, single HTTP request would:

Go through a LoginMethodFilter.

Then go through an AuthenticationFilter.

After that go through an AuthorizationFilter.

Finally hit the servlet.




