---
layout: post
type: "react hooks"
date: '2021-03-30'
---

## React Hooks

Hooks are the new feature introduced in the React 16.8 version. It allows you to use state and other React features without writing a class. Hooks are the functions which "hook into" React state and lifecycle features from function components. Also, it does not replace your knowledge of React concepts.Hooks are functions that let you “hook into” React state and lifecycle features from function components. Hooks don't work inside classes — they let you use React without classes.

## How hooks work in react?
A Hook is a react function that lets you use state and react features from a function based component. Hooks let you use the functions instead of switching between HOCs, Classes, and functions. As Hooks are regular Javascript functions, thus you can use the built-in Hooks and create your own custom one.Granted, you probably won't be tempted to call useState('name') twice in the same component except by mistake. ... The actual Hooks proposal solves this by relying on the call order: even if two Hooks use a name state variable, they would be isolated from each other. Every useState() call gets its own “memory cell”.
