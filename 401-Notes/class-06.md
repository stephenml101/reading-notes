# [Objects and Classes](https://docs.oracle.com/javase/tutorial/java/concepts/)

1. What is the difference between an Object and a Class in Java?

- An object is a software bundle of related state and behavior. A class is a blueprint or prototype from which objects are created.

2. Explain to a non-technical friend the concept of inheritance in Java.

- Just like children inherit traits from their parents, objects can also inherit traits from a main object.

[Java Static Keyword](https://www.programiz.com/java-programming/static-keyword)

1. Static methods are also called what? Why?

- class methods, because a static method belongs to the class rather than the object of a class.

2. How can you access a variable of a class without instantiating an object from that class?

- Using methods of that class for example: 

``` java
class Test {
    // regular variable
   int age;
}

class Main {
    // create instances of Test
    Test test1 = new Test();
    Test test2 = new Test();
}
```

[Java Singleton Class](https://www.programiz.com/java-programming/singleton)

1. What is a Design Pattern? Describe one or two with analogies from your previous work experience.

- A design pattern is like our code library that includes various coding techniques shared by programmers around the world.

- Bootstrap is a great example.

What is a Singleton?

- Singleton is a design pattern rather than a feature specific to Java. 

