## Async Functions

Are used to tell the browser to proceed once a certain function was executed.
It is returning a promise which informs about the status of the function.

In order to make use of async functions functions need to be declared as async by adding the keyword `async` as follows:  
`async function functionName() {....}`  
Or as anonymous function  
`... ("event", async () => {...})`

Calling an async function can be done with the keyword `await` before calling the function. Like this:  
`await functionName()`

Now the further JavaScript will be executed once the function call is **finished**.

### Fetching APIs

Async functions are used to e.g. fetch information from an API like this
`const responst = await fetch(API-url)`  
Afterwards the fetched information are stored in JSON file and need to be changed to JavaScript with  
`const data = await response.json()`
