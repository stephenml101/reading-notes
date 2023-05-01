# [Spring App Basics](https://spring.io/guides/gs/serving-web-content/)

1. What role do the @Controller classes play in a Spring MVC application?

- In Spring’s approach to building web sites, HTTP requests are handled by a controller. You can easily identify the controller by the @Controller annotation.

2. Explain to a non-technical friend what a GET request is.

- A ``GET`` request allows a computer programmer to request information from an outside source.

3. What annotation should be placed on your Spring Boot application class?

- @Configuration: Tags the class as a source of bean definitions for the application context.

- @EnableAutoConfiguration: Tells Spring Boot to start adding beans based on classpath settings, other beans, and various property settings. For example, if spring-webmvc is on the classpath, this annotation flags the application as a web application and activates key behaviors, such as setting up a DispatcherServlet.

- @ComponentScan: Tells Spring to look for other components, configurations, and services in the com/example package, letting it find the controllers.

[Spring MVC and Thymeleaf](https://www.thymeleaf.org/doc/articles/springmvcaccessdata.html)

1. What method allows for a variable defined in Java (in your Spring Controller) to be dispalyed in HTML with the help of Thymeleaf?

- Model Attributes

2. Explain the role of a @Controller class in a Spring MVC application.

- Responsible for preparing a model map with data and selecting a view to be rendered.

3. What is a model attribute refered to in Thymeleaf?

- Allows for the complete abstraction of the view technology and, in the case of Thymeleaf, it is transformed into a Thymeleaf context object (part of the Thymeleaf template execution context) that makes all the defined variables available to expressions executed in templates.