---
layout: post
type: "Adding a delete button in react"
date: 2021-04-20
---

## Adding a delete button in react

In the <Item/> component we are using a value stored in the props object to initialize the state.
Now, in the </Item> component, we can accept the data carried by the props object and use it to initialize the state of the <Item/> component!
Then now we have a button to delete an item on each item rendered.
Only thing to do is to move todos to state in TodoList and pass the index of the current todo in to the removeItem method. Then splice it as you suggested. We can set a flag for the todo data and on initializing that data we can set the flag as true and when we delete the todo list we can set the flag as false.Every time you want to modify something in React, for example a list where you want to remove an item, you have to use React's state management. We will be using React's useState Hook here, for the sake of keeping the first example simple, however, you can also use React's useReducer Hook, as you will see later.