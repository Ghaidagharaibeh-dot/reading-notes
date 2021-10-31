# Spring Authorization

## Spring Boot and OAuth2
- OAuth2 use to do various things with "social login".
- It starts with a simple, single-provider single-sign on
- client have a choice of authentication providers: GitHub or Google.

## To bulid single-page apps using OAuth2 we need
- Spring Boot and Spring Security on the back end
- jQuery on the front end,But, the changes needed to convert to a different JavaScript framework or to use server-side rendering would be minimal.
- native OAuth 2.0 support in Spring Boot.

## The features of using OAuth2
- simple: a very basic static app with just a home page and unconditional login via Spring - - Boot’s OAuth 2.0 configuration properties .
- click: adds an explicit link that the user has to click to login.
- logout: adds a logout link as well for authenticated users.
- two-providers: adds a second login provider so the user can choose on the home page which one to use.
- custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.