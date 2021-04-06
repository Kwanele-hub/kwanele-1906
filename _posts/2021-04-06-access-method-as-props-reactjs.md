---
layout: post
type: "How to access method as props reacts Js"
date: 2021-04-06
---

## access method as props reacts Js
First pass event handlers and other functions as props to child components, you need to have access to the parent component in the handler, you also need to bind the function to the component instance.Using Function.prototype.bind in render creates a new function each time the component renders, which may have performance implications....
## How to access method as props reacts Js
 make a new component named ParentComponent.js.set a state to greet our parent whenever this component is rendered, setting a state  makes an application more dynamic. Also,make an event that gives an alert whenever the parent component is rendered.bind the event so that the this keyword won’t return “undefined“.Make a new component. Let’s call this ChildComponent.js, and make a simple functional component. Let’s make a simple button, and then pass the method greetParent() as a property. Essentially, the button must greet the parent when it is clicked.import the ChildComponent in ParentComponent.
