## CSS Grid

[Link to challenge & handout](https://github.com/neuefische/bo-web-23-1/tree/main/sessions/css-grid)  
[Cheatsheet](https://grid.malven.co/)

Is a enhancement / different solution to flexbox. It is good to use for `layouts of entire pages` and works like a table.

`display: grid;` to the parent element to open the grid.
Start of the grid for columns and rows is always 1, the end of the last row or column is always considered -1.

`gap: xx;`words the same way it does for flexbox.

`grid-template-columns /-rows: value;` allows you to define `how many rows and columns` you need and `how big they should be`. A common value is `xfr` which is working like `flex-grow`.
If several columns or rows of the same width / height are required you can use `repeat(number-of-repetition, width/height)`.

`grid-colum: value; / grid-row: value;` Can be used to tell the child element where to start and where to end at a column.
Value is separated by `/` the value `(number) before the /` tells at which column/row the element needs to start and `after the /` where to end. Instead of a number `span x` can be used to tell the item over how many columns/rows it should span.

### Grid Template Areas

You can also predefine the structure of of the grid like this:
`grid-template-areas:`  
`"a b c"`
`"a b c";`

Afterwards you can assigned the values `a, b, c` to the childs and they will automatically align in the grid.
