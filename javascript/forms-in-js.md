## Forms in JavaScript

Listen to the `"submit"` event of a form, grab the `event` and `prevent its default`.

Afterwards, first collect the information  
`const formData = new FormData(event.target)`  
and afterwards store in object  
`const data = Object.fromEntries(formData)`

Now the data can be handled and the values be accessed.
