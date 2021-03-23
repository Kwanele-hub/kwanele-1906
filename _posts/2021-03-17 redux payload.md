---
layout: post
type: "redux payload"
date: 2021-03-17
---
## Redux payload

## what is redux payload?
Payload is the key value pairs in your actions and passed around between reducers in your redux application.

example: 

const someAction = { type: "Test", payload: {user: "Test User", age: 25}, }.

Each action creator contains an action and payload which contains the data we need to pass to the reducers. 

const data = 'sample data here' return { type: 'SELECT_ACCOUNT', payload: data }

 ## action object has a type:

{
  type: "DELETE_POST",
  id: 123
}
besides the type, it usually has some kind of data that provides more information about this action.it is called "payload".
Payload is a non-official, community accepted naming convention for the property that holds the actual data in a Redux action object.
using payload just gives you a consistent name that you know will exist in every action.