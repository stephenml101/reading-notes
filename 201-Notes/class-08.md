# Notes
## Things I want to know more about:

[Flexbox](https://web.dev/learn/css/flexbox/)

1. Flexbox is designed for one-dimensional content. Explain what this means.

- It excels at taking a bunch of items which have different sizes, and returning the best layout for those items.

2. Explain the difference between the main axis and cross axis.

- The main axis is the one set by your flex-direction property. If that is row your main axis is along the row, if it is column your main axis is along the column.

- The cross axis runs in the other direction to the main axis, so if flex-direction is row the cross axis runs along the column.

3. How can using certain properties of flexbox negatively impact accessibility?

- You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

[Flexbbox CSS Layout](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

1. What are some advantages of using flexbox over float?

- Vertically centering a block of content inside its parent.

- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

2. How does this topic connect with your long term goals?

It will allow me to become a better CSS programmer.