---
layout: post
type: "Redux store"
date: 2021-03-05
---
## Redux store

Redux is a state container for JavaScript apps, called a Redux store. It stores the whole state of the app in an immutable object tree. To create a store the createStore(reducer, [initialState], [enhancer]) function is used to create a new store. It takes three arguments: reducer - A reducing function.
Redux is a predictable state container designed to help you write JavaScript apps that behave consistently across client, server, and native environments and are easy to test. While it's mostly used as a state management tool with React, you can use it with any other JavaScript framework or library.

The state in Redux is stored in memory, in the Redux store. This means that, if you refresh the page, that state gets wiped out. The state in redux is just a variable that persists in memory because it is referenced  by all redux functions.
With redux, you would ideally store as little component state in your react components themselves and instead move that to the redux state tree. I believe a good point to start incorporating redux is when your app gets to a certain point where your components are no longer just "dumb" components that display data