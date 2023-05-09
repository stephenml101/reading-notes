# [Read (no need to do) this tutorial on OAuth](https://spring.io/guides/tutorials/spring-boot-oauth2/)

1. In non-technical terms, describe what using OAuth can provide for your application.

- simple: a very basic static app with just a home page and unconditional login via Spring Boot’s OAuth 2.0 configuration properties (if you visit the home page, you will be automatically redirected to GitHub).

- click: adds an explicit link that the user has to click to login.

- logout: adds a logout link as well for authenticated users.

- - two-providers: adds a second login provider so the user can choose on the home page which one to use.

custom-error: adds an error message for unauthenticated users, and a custom authentication based on GitHub’s API.

2. Which authentication providers are covered in the tutorial?

- GitHub and Google