## Things I want to know more about

These notes deal with learning the basics about CSS.

[What is CSS?](https://developer.mozilla.org/en-US/docs/Learn/CSS/First_steps/What_is_CSS)

*  Using CSS, you can control exactly how HTML elements look in the browser, presenting your markup using whatever design you like.
* Browsers are the main type of user agents we think of when talking about CSS, however, they are not the only ones. There are other user agents available, such as those that convert HTML and CSS documents into PDFs to be printed.

**CSS can be used for:**
* changing the color and size of headings and links
* creating a layout 
* Animations
* Etc

Example of CSS:
h1 {
  color: red;
  font-size: 5em;
}

p {
  color: black;
}

* [How to add CSS](https://www.w3schools.com/css/css_howto.asp)

There are three ways of inserting a style sheet:

1. External CSS
2. Internal CSS
3. Inline CSS

**External**- you can change the look of an entire website by changing just one file

* An external style sheet can be written in any text editor, and must be saved with a .css extension.
* The external .css file should not contain any HTML tags.

**Internal**- An internal style sheet may be used if one single HTML page has a unique style.

* The internal style is defined inside the style element, inside the head section.

**Inline**- An inline style may be used to apply a unique style for a single element.

* To use inline styles, add the style attribute to the relevant element. The style attribute can contain any CSS property.

* [CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS/Reference)

* [Myers Wed Reset Style Sheet](https://meyerweb.com/eric/tools/css/reset/)