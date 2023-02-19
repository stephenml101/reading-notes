# Notes

## Things I want to know more about:

* [Domain Modeling](https://github.com/codefellows/domain_modeling#domain-modeling)

1. Explain why we need domain modeling.

- Domain modeling is the process of creating a conceptual model for a specific problem. And a domain model that's articulated well can verify and validate your understanding of that problem.


* [HTML Table Basics](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Basics)

1. Why should tables not be used for page layouts?

- Layout tables reduce accessibility for visually impaired users.

- Table layouts generally involve more complex markup structures than proper layout techniques. This can result in the code being harder to write, maintain, and debug.

- Tables are not automatically responsive

2. List and describe 3 different semantic HTML elements used in an HTML table.

* td- The smallest container inside a table is a table cell, which is created by a td element ('td' stands for 'table data')

* tr- table row

* th- table head

* [Constructors](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/Basics#introducing_constructors)

1. What is a constructor and what are some advantages to using it?

Constructors are used to create more than one object.
A constructor is just a function called using the new keyword. When you call a constructor, it will:

- create a new object
- bind this to the new object, so you can refer to this in your constructor code
- run the code in the constructor
- return the new object.


2. How does the term this differ when used in an object literal versus when used in a constructor?

- this keyword refers to the current object the code is being written inside — so in this case this is equivalent to person.

- when you only have to create a single object literal, it's not so useful. But if you create more than one, this enables you to use the same method definition for every object you create.

* [Object Prototypes Using A Constructor](https://ui.dev/beginners-guide-to-javascript-prototype)

1. Explain prototypes and inheritance via an analogy from your previous work experience.

- Prototype object will have a constructor property which points to the original function or the class that the instance was created from.

* [HTML Table Advanced Features and Accessibility](https://developer.mozilla.org/en-US/docs/Learn/HTML/Tables/Advanced)