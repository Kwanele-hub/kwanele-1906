---
layout: post
type: "Redux components"
date: 2021-03-19
---
## Redux components

Redux has three building parts: actions, store, and reducers.#Actions are the only source of information for the store as per Redux official documentation. It carries a payload of information from your application to store. actions are plain JavaScript object that must have a type attribute to indicate the type of action performed.
#A reducer is a function that determines changes to an application's state. It uses the action it receives to determine this change. the're tools like Redux, that help manage an application's state changes in a single store so that they behave consistently.