 # Spring Authentication

 
 ### Difference between authentication and authorization.

Authentication : is the process of knowing the identity of the user. also known as access control.

Authorization (access control) : is the process of what that particular user is allowed to access or do in the web application.


### Authentication

In spring the main interface for authentication is AuthenticationManger which has only one method which is authenticate which can be used to do 3 main things:

Return an Authentication with value of authenticated = true if it can verify that the input represents a valid principle.

Throw an AuthenticationException if the input represents an invalid principle.

Return null if it can’t decide.

```
public interface AuthenticationManager {

  Authentication authenticate(Authentication authentication)
    throws AuthenticationException;
}
```

![](https://raw.githubusercontent.com/spring-guides/top-spring-security-architecture/main/images/authentication.png)


Customizing Authentication Managers

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


### Authorization or Access Control

Once we authenticate the user to be able to access the website, now we need to limit the access of that particular user to the website content.

For an example a generic user access to the website is different than the administrative access.

To do that we use AccessDecisionManager as out main strategy.




