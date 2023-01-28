## Display flex in CSS

To change the default layout of (especially) HTML block elements you make use of the CSS-property `display: flex;` which needs to be applied to the `parent / container`element.

### General information

By default once `display: flex;`is applied to the parent element, the child elements will be ordered in `row`.
There are several different further properties for the parent element and the child element to change the layout

### Properties for parent element

`flex-direction: column` changes that the childs are stacked on top of each other. In general it tells the behavior on the main-axis which is `horizontally for row` and `vertically for column` which is important for further properties. Depending on this the secondary axis will be the other axis.

- `row` moves childs from top to bottom HTML order from left to right (default value)
- `row-reverse` moves childs from top to bottom HTML order from right to left (other way around)
- `column` childs will be displayed top to bottom just like in HTML
- `column-reverse` childs will the displayed top to bottom but other way around than in HTML

`justify-content: value` is how the child elements should behave on the **main axis** so where they should be. The available and most common values are:

- `flex-start` at the beginning of the container next to each other (default value)
- `flex-end` at the end of the container next to each other
- `center` in the middle of the container next to each other
- `space-around` with the remaining space evenly divided to all elements (including the edge of the container)
- `space-between` with the remaining space evenly divided to all elements (exclufing the edge of the container, first and last element will be at the edge)

`align-items: value` is how the child elements should behave on the **secondary axis** so where they should be. The available and most common values are:

- `flex-start` at the beginning of the container(default value)
- `flex-end` at the end of the container
- `center` in the middle of the container
- `baseline` evenly at the bottom of text (if given)

`flex-wrap: value` defines how items should be have if less space is given

- `no-wrap` the childs themselfes are deceasing too (default)
- `wrap` the childs themselfes are breaking row and moving underneath each other

**`flex-direction` and `flex-wrap` can be combined with the property `flex-flow: column wrap;`. First value defines the direction, second one the wrap behvior**

### Properties for childs

Child elements need to be separately selected in CSS to apply the custom styles.

`order: number;` Allows you to change the order of the elements in the parent container. By default all elements have the `order: 0;` and are therefore listed in the order they are in HTML. By giving them values such as `-1`and `1`the order will be changed.

`align-self: value` Works like `align-items` but for the individual child

`justify-self: value;` Works like `justify-content`but for the individual child
