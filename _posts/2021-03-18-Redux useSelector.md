---
layout: post
type: "Redux useSelector"
date: 2021-03-18
---
## Redux useSelector

UseSelector is a function that takes the current state as an argument and returns whatever data you want from it. It's very similiar to mapStateToProps() and it allows you to store the return values inside a variable within the scope of you functional components instead of passing down as props.With useSelector(), returning a new object every time will always force a re-render by default. If you want to retrieve multiple values from the store, you Call useSelector() multiple times, with each call returning a single field value.

## Using the useSelector Hook in a React Redux App

The selector will be called with the entire Redux store state as its only argument. The selector function may return any value as a result, not just an object. The return value of the selector will be used as the return value of the useSelector hook.The useReducer React hook provides a Redux-like means of managing state transitions, but it's no replacement for Redux when it comes to managing a global application state tree. ... Even better, hooks can be composed into larger units of functionality that can be mixed into any number of components.