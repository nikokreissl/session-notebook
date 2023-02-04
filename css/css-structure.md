## CSS structure

[Link to challenge & hangout](https://github.com/neuefische/bo-web-23-1/blob/main/sessions/css-structure/css-structure.md)

### BEM

Is a methodology how CSS classes should be called

The rules are:

- Block = Standalone element `class="block"`
- Element = Part of a block, not alone `class="block__element"`
- Modifier = Changes the HTML element `class="block__element--modifier"`

### Splitting css classes

To keep track of the different styles that were applied to certain parts css files can be separated.

In the HTML you only need to link `one file` and in this one file the `other files are imported` like this:
`@import "filename".

### CSS custom porperties

You can declare variables in CSS like this:
`--custom-property: value;`  
You can use it like this:  
`color: var(--custom-property);`  
Like this a e.g. color can be applied to multiple elements and be changed at all places at a single place.
