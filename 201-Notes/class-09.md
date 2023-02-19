# Notes

## Things I want to know more about:

[HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

1. Why are forms so important in web development?

Web forms are one of the main points of interaction between a user and a website or application. Forms allow users to enter data, which is generally sent to a web server for processing and storage.

2. When designing a form, what are some key things to keep in mind when it comes to user experience?

- From a user experience (UX) point of view, it's important to remember that the bigger your form, the more you risk frustrating people and losing users. Keep it simple and stay focused: ask only for the data you absolutely need.

3. List 5 form elements and explain their importance.

- The fieldset element is a convenient way to create groups of widgets that share the same purpose, for styling and semantic purposes

-The text content of the legend formally describes the purpose of the fieldset it is included inside.

- The label element is the formal way to define a label for an HTML form widget. This is the most important element if you want to build accessible forms

- The form element creates the form.

- The button element creates a clickable button.

[Introduction To Events](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Building_blocks/Events)

1. How would you describe events to a non-technical friend?

- Events are things that happen in the system you are programming — the system produces (or "fires") a signal of some kind when an event occurs, and provides a mechanism by which an action can be automatically taken (that is, some code running) when the event occurs.

2. When using the addEventListener() method, what 2 arguments will you need to provide?

- String to listen to the event and a function to call when the event happens.

3. Describe the event object. Why is the target within the event object useful?

- Sometimes, inside an event handler function, you'll see a parameter specified with a name such as event, evt, or e. This is called the event object, and it is automatically passed to event handlers to provide extra features and information. The target property of the event object is always a reference to the element the event occurred upon.

4. What is the difference between event bubbling and event capturing?

- Event bubbling describes how the browser handles events targeted at nested elements.

- Event capturing is like event bubbling but the order is reversed: so instead of the event firing first on the innermost element targeted, and then on successively less nested elements, the event fires first on the least nested element, and then on successively more nested elements, until the target is reached.

[HTML5 Input Types](https://developer.mozilla.org/en-US/docs/Learn/Forms/HTML5_input_types)

[Event reference and listings](https://developer.mozilla.org/en-US/docs/Web/Events)


