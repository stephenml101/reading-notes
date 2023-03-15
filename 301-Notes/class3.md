## Things I want to know more about:

[React Docs - lists and keys](https://reactjs.org/docs/lists-and-keys.html)

1. What does .map() return?

- It return whatever you want to do to items in an array.

2. If I want to loop through an array and display each value in JSX, how do I do that in React?

- using curly braces {}

3. Each list item needs a unique ____.

- Key

4. What is the purpose of a key?

- Keys help React identify which items have changed, are added, or are removed. Keys should be given to the elements inside the array to give the elements a stable identity

[The Spread Operator](https://medium.com/coding-at-dawn/how-to-use-the-spread-operator-in-javascript-b9e4a8b06fab)

1. What is the spread operator?

- The spread operator is a useful and quick syntax for adding items to arrays, combining arrays or objects, and spreading an array out into a function’s arguments.

2. List 4 things that the spread operator can do.

- Copying an array
- Concatenating or combining arrays
- Using Math functions
- Using an array as arguments

3. Give an example of using the spread operator to combine two arrays.

![Combine Arrays](/img/Comine-arrays.jpeg)


4. Give an example of using the spread operator to add a new item to an array.

![Add a new item to an array](/img/AddNewItem.png)

5. Give an example of using the spread operator to combine two objects into one.

![Two Objects](/img/TwoObjectsintoOne.png)

[How to Pass Functions Between Components](https://www.youtube.com/watch?v=c05OL7XbwXU)

1. In the video, what is the first step that the developer does to pass functions between components?

- Create the function wherever the state is you are going to change

2. In your own words, what does the increment function do?

- It adds the number to the people object based on how many times the button is clicked.

3. How can you pass a method from a parent component into a child component?

- Pass it using the same name. this.props.increment

4. How does the child component invoke a method that was passed to it from a parent component?

- Use the same name that was passed with this.

[React Tutorial through ‘Declaring a Winner’](https://reactjs.org/tutorial/tutorial.html)

[React Docs - Lifting State Up](https://reactjs.org/docs/lifting-state-up.html)