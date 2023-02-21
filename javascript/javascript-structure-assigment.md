## JavaScript Structure Assigment

Allows to easily create new variables based on an object or an array.

`const {prop-key, prop-key,...} = object` will check for the keys within the object and create new variables with the value putside the object.
**The variable name has to match the key of the property in the object**

Assign a new name to the property you want to get like this `const {prop-key: newVarName} = object` or add a default value that will be used if the object itself does not have the property `const {defaultValue = "default value", prop-key,...} = object`.

**--> works same way with Arrays**

### Rest Operator

Allows to collect all remaining information within an object. E.g.  
`const obj = {key1 = "value1", key2 = "value2", key3 = "value3"}`
With `const {key1, ...restOfTheObject} = obj` you would now have `const key1 = "value1"` and `const restOfTheObject = {key2 = "value2", key3 = "value3"}`.

### Spread Operator

Allows to append objects to other objects within the same scope.  
`const arr1 = ["string", 23]`  
`const arr2 = [true]`  
With `const arr1 = ["string", 23, ...arr2]` the array would look like this  
`const arr1 = ["string", 23, true]`
