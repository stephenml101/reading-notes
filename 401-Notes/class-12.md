# Setup

[Spring guide: Accessing Data with JPA](https://spring.io/guides/gs/accessing-data-jpa/)

1. How are query methods defined when using Spring Data JPA?

- By declaring their method signature. For example, CustomerRepository includes the ```findByLastName()```method.

2. Which dependencies will you need in order to complete the Spring guide?

``` java
import jakarta.persistence.Entity;
import jakarta.persistence.GeneratedValue;
import jakarta.persistence.GenerationType;
import jakarta.persistence.Id;
```

3. What annotations are used to specify an auto generated identification number for an Entity?

``` java
  @Id
  @GeneratedValue(strategy=GenerationType.AUTO)
```

[Baeldung: Comparing repositories](https://www.baeldung.com/spring-data-repositories)

1. Which of the Spring Data Repositories covered in the readings has the most methods available to it?

- PagingAndSortingRepository 

2. Name a downstide of a Spring Data Repository.

- By extending e.g. CrudRepository, we expose a complete set of persistence method at once. This is probably fine in most circumstances as well but we might run into situations where we'd like to gain more fine-grained control over the methods exposed, e.g. to create a ReadOnlyRepository that doesn't include the save(…) and delete(…) methods of CrudRepository

3. How would you define an operation to find a student based on their name in a repo named StudentRepository which extends JpaRepository?

``` java
List<T> findAll(Sort sort);
```