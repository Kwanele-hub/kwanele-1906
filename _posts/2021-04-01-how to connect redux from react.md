---
layout: post
type: "how to connect redux from react"
date: 2021-04-01
---

## How to connect redux from react
Connecting the Components#. React Redux provides a connect function for you to read values from the Redux store.React Redux includes its own custom hook APIs, which allow your React components to subscribe to the Redux store and dispatch actions. 

## How do I connect to react-redux?
import * as actionCreators from './actionCreators'
import { bindActionCreators } from 'redux'
function mapStateToProps(state) {
return { todos: state. todos }
function mapDispatchToProps(dispatch) {
return { actions: bindActionCreators(actionCreators, dispatch) }

## How do I use Redux with React JS?
For this we go inside src/index. js, we import a Provider from react-redux, and the newly created store like so: import { Provider } from "react-redux"; import configureStore from "store"; Provider: makes the Redux store available to any nested components that have been wrapped in the connect function.

