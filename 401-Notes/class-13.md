# Readings

[Related data in Spring (only read section “3. One-to-Many Relationship”)](https://www.baeldung.com/spring-data-rest-relationships)

1. Name a few real life examples of “One To Many” relatioships.

- Store to employees

2. Given two entities, one named Player and one named Team, if you wanted to create a one to many relationship with those entities which would be the one and which would be the many?

- Players: Many
- Team: One

3. Explain one to many relationships to a non-technical friend.

- There are many employees in one store.

[Baeldung: Spring Integration Testing](https://www.baeldung.com/integration-testing-in-spring)

1. Describe the difference between a unit test and an integration test.

- Unit test: We can enable this extension by adding the ```@ExtendWith``` annotation to our test classes and specifying the extension class to load. To run the Spring test, we use SpringExtension.class. 

- Integration test: Use static imports from the MockMvcRequestBuilders or MockMvcResultMatchers classes.
 

2. What is the object that provides support for Spring MVC Testing?

- MockMvc

3. What does the “perform()” method do in a Spring integration test?

- The ```perform()``` method will call a GET request method, which returns the ResultActions. Using this result, we can have assertion expectations about the response, like its content, HTTP status, or header.