## Things I want to know more about:

[React Docs - Forms](https://reactjs.org/docs/forms.html)

1. What is a ‘Controlled Component’?

- An input form element whose value is controlled by React

2. Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.

- As they enter them. Since handleChange runs on every keystroke to update the React state, the displayed value will update as the user types.

3. How do we target what the user is entering if we have an event handler on an input field?

- When you need to handle multiple controlled input elements, you can add a name attribute to each element and let the handler function choose what to do based on the value of event.target.name.

[The Conditional (Ternary) Operator Explained](https://codeburst.io/javascript-the-conditional-ternary-operator-explained-cac7218beeff)

Why would we use a ternary operator?

- To shorten an if statement into one line of code

Rewrite the following statement using a ternary statement:

![if statement](/img/ifstatement.png)

x===y ? console.log(true) : console.log(false)


[React Bootstrap - Forms](https://react-bootstrap.github.io/forms/overview/)

[React Docs - conditional rendering](https://reactjs.org/docs/conditional-rendering.html)
