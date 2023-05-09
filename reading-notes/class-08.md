# Readings: CSS Layout

## Flexbox is designed for one-dimensional content. Explain what this means.

It excels at taking a bunch of items which have different sizes, and returning the best layout for those items. This is the ideal layout model for a sidebar pattern. Flexbox not only helps lay the sidebar and content out inline, but where there's not enough space remaining, the sidebar will break onto a new line. 
Instead of setting rigid dimensions for the browser to follow, with flexbox, you can instead provide flexible boundaries to hint how the content could display.

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

## Explain the difference between the main axis and cross axis.

- The **main axis** is the one set by your `flex-direction` property. If that is `row` your main axis is along the row, if it is `column` your main axis is along the column.

- The **cross axis** runs in the other direction to the main axis, so if `flex-direction` is `row` the cross axis runs along the column.

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

## How can using certain properties of flexbox negatively impact accessibility?

You should be cautious when using any properties that reorder the visual display away from how things are ordered in the HTML document, as it can negatively impact accessibility. The `row-reverse` and `column-reverse` values are a good example of this. The reordering only happens for the visual order, not the logical order. This is important to understand as the logical order is the order that a screen reader will read out the content, and anyone navigating using the keyboard will follow.

[Learn CSS - Flexbox](https://web.dev/learn/css/flexbox/)

## What are some advantages of using flexbox over float?

- Vertically centering a block of content inside its parent.

- Making all the children of a container take up an equal amount of the available width/height, regardless of how much width/height is available.

- Making all columns in a multiple-column layout adopt the same height even if they contain a different amount of content.

[CSS Layout - Flexbox](https://developer.mozilla.org/en-US/docs/Learn/CSS/CSS_layout/Flexbox)

## How does this topic connect with your long term goals?

Understanding and mastering Flexbox would be very beneficial in my long term goals as a programmer because it will allow me to improve my workflow, code more efficiently, and help create more accessible websites.
