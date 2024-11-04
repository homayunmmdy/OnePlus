## Function as First Class Citizen
In javascript 
- we can assign function into variable
- we can pass it as an argument
- we can also return function into another function

## Higher Order Functions
higher order function is function that takes the 
- funtion as an argument 
- or return the function

## Function Compositions
a powerful technique that allows developers to combine multiple functions into a single function

```javascript
const trim = str => str.trim();
const wrapInDiv = str => `<div>${str}</div>`
const toLowerCase = str => str.toLowerCase()

const result = wrapInDiv(toLowerCase(trim(input)))
```