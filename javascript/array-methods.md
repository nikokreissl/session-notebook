## Array methods

### General

- are using callback functions which tell the method what should happen
- are expecting a return

`arr.forEach(() => {})`  
To do something within the given array

`arr.map(() => {})`  
Creates a new array and stores according to callback in the new variable

`arr.filter(() => {})`  
Creates a new array and stores according to callback filters in the new variable

`arr.includes(() => {})`  
Checks if a value is given and returns true or false

`arr.find(() => {})`  
Checks for the first match and returns the value

`arr.findIndex(() => {})`  
Checks for the first match and returns the index. If no match found returns -1.

`arr.sort(() => {})`  
Sorts the array according to the callback  
**IMPORTANT!** changes the original array!

`arr.slice(() => {})`  
Creates a copy of the array. Optionally can add params to tell where the array should be copied

`arr.some(() => {})`  
Checks if at least one item to match the rules of the callback and returns true / false

`arr.every(() => {})`  
Checks if at all items match the rules of the callback and returns true / false.
