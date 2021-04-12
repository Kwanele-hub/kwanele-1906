---
layout: post
type: "Callbacks in javascript"
date: 2021-04-12
---
## Callbacks
A callback is a function passed as an argument to another function. This technique allows a function to call another function. A callback function can run after another function has finished.Callbacks make sure that a function is not going to run before a task is completed but will run right after the task has completed. It helps us develop JavaScript code and keeps us safe from problems and errors.Callbacks are generally used when the function needs to perform events before the callback is executed, or when the function does not (or cannot) have meaningful return values to act on
# example:

the isOddNumber is a callback function. When you pass a callback function into another function, you just pass the reference of the function i.e. the function name without the parentheses () .

 # example:

function greeting(name) { alert('Hello ' + name); } function processUserInput(callback) { var name = prompt('Please enter your name. '); callback(name); } processUserInput(greeting);