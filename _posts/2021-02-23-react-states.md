---
layout: post
type: "Ract states"
date: 2021-02-23
---
##React states

React components has a built-in state object. The state object is where you store property values that belongs to the component.
When the state object changes, the component re-renders.In a React component, props are variables passed to it by its parent component. 
State on the other hand is still variables, but directly initialized and managed by the component. The state can be initialized by props.



A setState() schedules an update to a component’s state object. When state changes, the component responds by re-rendering.
State can be anything, but think of things like whether a user is logged in or not and displaying the correct username based on which account is active. 
Or an array of blog posts. Or if a modal is open or not and which tab within it is active.

React components with state render UI based on that state. When the state of components changes, so does the component UI.
That makes understanding when and how to change the state of your component important.

## How do you define a state in a react function?
* We import the useState Hook from React. It lets us keep local state in a function component.
* Inside the Example component, we declare a new state variable by calling the useState Hook. It returns a pair of values, to which we give names. ...
* When the user clicks, we call setCount with a new value.



