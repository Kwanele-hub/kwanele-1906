---
layout: post
type: "javascript underscores"
date: 2021-05-03
---

## Javascript underscores

Underscore (_) is a valid variable identifier in JavaScript, and could refer to anything.Developers use it to signify the meaning or scope of the variable. In this case it looks like it is telling the developer this variable should be a local or private variable.

## Use Underscore in Node. js
var _ = require('underscore');
var numbers = [1, 2, 5, -3];
var squares = _. map(numbers, function(x) { return x*x; });
console. log(squares);

Underscore. js is a utility library that is widely used to deal with arrays, collections and objects in JavaScript. It can be used in both frontend and backend based JavaScript applications. Usages of this library include filtering from array, mapping objects, extending objects, operating with functions and more.