## JavaScript Basics

[Link to handout and challenges](https://github.com/neuefische/bo-web-23-1/tree/main/sessions/js-basics)

### Console

The console is used to debug and echo any input if wanted. The main commands are

- `console.log()` = Logs any input to the console
- `console.clear()` = Clears any input given to console
- `console.error()` = Logs to console but in red

### DOM Manipulation

DOM (DOcument Object Modal) is the structure of the HTML element with the CSS styles. With JavaScript you can access these elements and change their appearance and behavior.
This is called `DOM Manipulation`

### Call elements

To select elements you should always use a **separate attribute** and not use e.g. any given CSS class -> `Separation of concern` to keep things clearly apart.

Add this attribute to any element you want to select with JavaScript:

`data-js: element-name;`

You can then select an element like this

**const var = document.querySelector('["data-js: element-name"]')**

### Variables

Variables are used to store information and also selected HTML elements in it. You can write anything as name but it shoule be `clear what the variable is about` and it should be written in `camel-case` (start lower case letter, eveyadditional word first letter to be upper case e.g. `thisIsAnExample`.

Variables can be created woth `const` which means they can not be changed and `let` which means they can be changed. It is recommended to work primarly with `const` since it can be controlled better.
