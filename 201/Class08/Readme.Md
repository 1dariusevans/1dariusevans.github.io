Learn CSS - Flexbox
Flexbox is designed for one-dimensional content. Explain what this means.
The Flexible Box Layout Model (flexbox) is a layout model designed for one-dimensional content. It excels at taking a bunch of items which have different sizes, and returning the best layout for those items. This is the ideal layout model for this sidebar pattern.
Explain the difference between the main axis and cross axis.
The main axis is defined by flex-direction, which has four possible values:
row
row-reverse
column
column-reverse
The cross axis runs perpendicular to the main axis, therefore if your flex-direction (main axis) is set to row or row-reverse the cross axis runs down the columns.
How can using certain properties of flexbox negatively impact accessibility?
You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The row-reverse and column-reverse values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.
CSS Layout - Flexbox
Read up to “Flex-Flow Shorthand”
What are some advantages of using flexbox over float?
For a long time, the only reliable cross-browser compatible tools available for creating CSS layouts were features like floats and positioning. These work, but in some ways they’re also limiting and frustrating.
The following simple layout designs are either difficult or impossible to achieve with such tools in any kind of convenient, flexible way:
Vertically centering a block of content inside its parent.
Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.
Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.
How does this topic connect with your long term goals?
Well, anything that is designed to save time or be easier to use; will be beneficial to me


Journal Learning:

