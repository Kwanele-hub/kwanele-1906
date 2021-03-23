---
layout: post
type: "redux reducer"
date: 2021-03-16
---
## Redux reducer

A reducer is a function that determines changes to an application's state. It uses the action it receives to determine the change. Redux relies heavily on reducer functions that take the previous state and an action in order to execute the next state.The redux reducer is called a reducer is because you could "reduce" a collection of actions and an initial state (of the store) on which to perform these actions to get the resulting final state .The reducer is a pure function that takes the current state and an action, and returns the next state.An action, is an object that contains the payload of information. They are the only source of information for the Redux store to be updated. Reducers update store based on the value of the action.The concept of a Reducer became popular in JavaScript with the rise of Redux as state management solution for React. ... Basically reducers are there to manage state in an application.