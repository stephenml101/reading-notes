# In Memory Storage Notes:

[Understanding the JavaScript Call Stack](https://medium.freecodecamp.org/understanding-the-javascript-call-stack-861e41ae61d4)

1. What is a ‘call’?

- A function invocation.

2. How many ‘calls’ can happen at once?

- Until the brower's maximum call size has been reached.

3. What does LIFO mean?

- Last In, First Out, it means that the last function that gets pushed into the stack is the first to be pop out, when the function returns.

4. Draw an example of a call stack and the functions that would need to be invoked to generate that call stack.

![Call](/img/Call.png)

5. What causes a Stack Overflow?

- A stack overflow occurs when there is a recursive function (a function that calls itself) without an exit point.

[JavaScript error messages](https://codeburst.io/javascript-error-messages-debugging-d23f84f0ae7c)

1. What is a ‘reference error’?

- This is as simple as when you try to use a variable that is not yet declared you get this type os errors.

2. What is a ‘syntax error’?

- This occurs when you have something that cannot be parsed in terms of syntax, like when you try to parse an invalid object using JSON.parse.

3. What is a ‘range error’?

- Try to manipulate an object with some kind of length and give it an invalid length and this kind of errors will show up.

4. What is a ‘type error’?

- This types of errors show up when the types (number, string and so on) you are trying to use or access are incompatible, like accessing a property in an undefined type of variable.

5. What is a breakpoint?

- The point right before the error happened.

6. What does the word ‘debugger’ do in your code?

- It can acheive the breakpoint.

[JavaScript errors reference on MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Errors)

## Thing I want to know more about.