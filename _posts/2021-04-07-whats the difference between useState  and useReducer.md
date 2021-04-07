---
layout: post
type: "what is the difference between useState and useReducer?"
date: 2021-04-07
---

## what is the difference between useState and useReducer

useReducer is usually preferable to useState when you have complex state logic that involves multiple sub-values or when the next state depends on the previous one. useReducer also lets you optimize performance for components that trigger deep updates because you can pass dispatch down instead of callbacks.The useReducer hook also can be used to update state, but it does so in a more sophisticated way: it accepts a reducer function and an initial state, and it returns the actual state and a dispatch function. The dispatch function alters state in an implicit way by mapping actions to state transitions: Use useState whenever you manage a JS primitive. Use useReducer whenever you manage an object or array.useReducer() is a method from the React Hooks API, similar to useState but gives you more control to manage the state. It takes a reducer function and initial state as arguments and returns the state and dispatch method:
A reducer (being called that because of the function type you would pass to an array methodArray.prototype.reduce(reducer, initialValue)) is a pattern taken from the Redux. If you are not familiar with Redux, in short, a reducer is a pure function that takes previous state and action as an argument, and returns the next state.
useReducer() is an alternative to useState() which gives you more control over the state management and can make testing easier. All the cases can be done with useState() method, so in conclusion, use the method that you are comfortable with, and it is easier to understand for you and colleagues.