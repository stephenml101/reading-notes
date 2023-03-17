## Things I want to know more about:

[React Docs - Thinking in React](https://reactjs.org/docs/thinking-in-react.html)

1.What is the single responsibility principle and how does it apply to components?

-  A component should ideally only do one thing. If it ends up growing, it should be decomposed into smaller subcomponents.

2. What does it mean to build a ‘static’ version of your application?

- It means building a version of your app with no interactivity.

3. Once you have a static application, what do you need to add?

- State

4. What are the three questions you can ask to determine if something is state?

- Does it remain unchanged over time? If so, it isn’t state.

- Is it passed in from a parent via props? If so, it isn’t state.

- Can you compute it based on existing state or props in your component? 

5. How can you identify where state needs to live?

- You need to identify which component is responsible for changing this state, or owns the state.

[Higher-Order Functions](https://eloquentjavascript.net/05_higher_order.html#h_xxCc98lOBK)

1. What is a “higher-order function”?

- Functions that operate on other functions, either by taking them as arguments or by returning them, are called higher-order functions.

2. Explore the greaterThan function as defined in the reading. In your own words, what is line 2 of this function doing?

- It is return m if m is greater than n.

3. Explain how either map or reduce operates, with regards to higher-order functions.

- map - The new array will have the same length as the input array, but its content will have been mapped to a new form by the function.

- reduce -  It builds a value by repeatedly taking a single element from the array and combining it with the current value. When summing numbers, you’d start with the number zero and, for each element, add that to the sum.


