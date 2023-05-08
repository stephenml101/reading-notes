# [Spring Security Overview](https://spring.io/guides/topicals/spring-security-architecture/)

1. What does it mean to authenticate a user?

- Authenticate a user means to verify who the user is.

2. What does it mean to authorize a user?

- Authorize means to control what the user us allowed to do.

3. What are the three possible outcomes of the AuthenticationManager’s authenticate() method?

-Return an Authentication (normally with authenticated=true) if it can verify that the input represents a valid principal.

- Throw an AuthenticationException if it believes that the input represents an invalid principal.

- Return null if it cannot decide.

[Spring Auth cheat sheet](https://github.com/codefellows/seattle-java-401d2/blob/master/SpringAuthCheatSheet.md)