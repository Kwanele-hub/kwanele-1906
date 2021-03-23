---
layout: post
type: "Connect Redux to React"
date: 2021-03-04
---
## Connect Redux to React

The connect() function connects a React component to a Redux store. It provides its connected component with the pieces of the data it needs from the store, and the functions it can use to dispatch actions to the store.React provides two major mechanisms for providing data to components: props and state. Props are read-only and allow a parent component to pass attributes to a child component. State is local and encapsulated within the component and can change at any time in the component’s lifecycle.

Redux is a predictable state container for JavaScript apps ranging from vanilla apps to framework apps. It has a very tiny footprint yet allows you to write consistent apps that can run in any environmentThe react-redux package provides React bindings for the Redux state container, making it very easy to connect a React application to a Redux store. This allows you to separate your React application components based on their connection to the Redux store