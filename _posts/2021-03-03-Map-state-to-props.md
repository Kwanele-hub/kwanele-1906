---
layout: post
type: "map state to props"
date: 2021-03-03
---


## React map state to props

MapStateToProps is used for selecting the part of the data from the store that the connected component needs. It's frequently referred to as just mapState 
It receives the entire store state, and return an object of data the component needs.
The Provider component allows you to provide state and dispatch to your React components you must specify exactly what state and actions you want. by this, you make sure that each component only has access to the state it needs. accomplish this by creating two functions: mapStateToProps() and mapDispatchToProps().
In these functions, you declare what pieces of state you want to have access to and which action creators you need to be able to dispatch. Once these functions are in place, you'll see how to use the React Redux connect method to connect them to your components .

Props is a special keyword in React, which stands for properties and is being used for passing data from one component to another.  props data is read-only, which means that data coming from the parent should not be changed by child components.