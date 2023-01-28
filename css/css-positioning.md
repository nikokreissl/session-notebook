## Positiong with CSS

HTML elements can be placed manually with CSS. By default they are static and placed in the regular HTML flow.

There are four ways to change thos

`position: relative`Changes the element so the position is relative to where it would actually be. It remains in the HTML flow!

`position: absolute`Changes the position of the element **within the next absolute** element. It is removed from the document flow.

`position: fixed`Removes the element from the document flow and it remains at a certain position

`position: sticky`Remains in its position until a certain offset is is reached. From there it scrolls along with the document.

The **offset** can be defined with the properties `top: value`, `bottom: value;`, `left: value`and `right: value`. Each of them tells how the element should be moved **from the certain position**. E.g. `top: 20px`moves the element `20px down`.

With the **z-index** you can define the stacking of the elements, so if they should appear in the background of other elements or not.
