## JavaScript Import and Export

To stick to separation of concern it is best practise to keep everything apart in JavScript just like in CSS.  
Therefore, import and export is used to create different places (files) and import them in the end.

To tell the browser you are importing files to `<script>` within the `html <head>` by adding `type="module"`. With that being done `defer` can also be removed from the script since it is a default value of `type="module"`.

### Export

To export a function or a variable from a file the keyword `export` needs to be added to **each** item that should be imported.

### Import

To import a exported item in the file where the item needs to be proceed as follows:  
`import {function / variable } from "location"`  
Afterwards the imported item can be used. To import multiple items from one file you can do that by **separating the names in the curly brackets with commas**.
