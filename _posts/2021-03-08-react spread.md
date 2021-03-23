---
layout: post
type: "React spread operator"
date: 2021-03-08
---
## React spread operator

The Spread operator lets you expand an iterable like a string, object or array into its elements while the Rest operator does the inverse by reducing a set of elemnts into one arraThe spread operator makes deep copies of data if the data is not nested. When you have nested data in an array or object the spread operator will create a deep copy of the top most data and a shallow copy of the nested data.


The spread operator is a new addition to the set of operators in JavaScript ES6. It takes in an iterable array and expands it into individual elements. The spread operator is commonly used to make shallow copies of JS objects.Spread syntax (...) allows an iterable like array expression or string to be expanded in places where zero or more arguments of function calls or elements for array literals are expected, or an object expression to be expanded in places where zero or more key-value pairs (for object literals) are expected.


example:

function sum(x, y, z) {
  return x + y + z;
}