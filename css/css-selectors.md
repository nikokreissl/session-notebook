## CSS-selectors

With CSS selectors you can change how a HTML element looks and even behaves to a certain point.
It is working descendant so if an element is selected twice the last selector applies.

There are different types of selectors.

[Link to challenges & handout](https://github.com/neuefische/bo-web-23-1/tree/main/sessions/css-selectors)

### Tag / Type selector

Selects an element based on their tag / type, e.g. `<h1>`

### Universal selector

`*` Selects all elements in the file

### Class selector

By starting a selector with `.` all elements with the class assigned

### Attribute selector

With `tag[type]` all elements of a tag with a **any type** are selected, e.g. `button[type]`

It can be enhanced by giving the attribute a value, e.g. `button[type="submit"]`

For a-tags you can tell the selector to only select hrefs starting with a certain pattern, e.g. external https links.
`a[href^="https"]`

### Pseudo classes

Pseudo classes are states of elements, e.g. on hover or when a input is active.
Additionally there are `::before` and `::after` can be used to paste content which will e.g. be ignored by screen readers
