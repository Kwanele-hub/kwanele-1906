---
layout: post
type: "How i find react interesting"
date: 2020-10-09
---

## How i find react interesting

React is a JavaScript library for building user interfaces.
It  was designed from the start for gradual adoption, where you can use as little or as much React as you need.

this is my first react app...
import React, { useState } from "react"

export default function Count() {
    const [count, setCount] = useState(0);

   const  add = ()=>{
        setCount(count + 1)
    }
    const reduce =()=>{
        setCount(count - 1)
    }

    return (
        <div>
            <p>Counter</p>
            <p>{count}</p>
            <button variant="primary" size="lg" active onClick={() => add()}>Increment</button>
            <button onClick={() => reduce()}>Decrement</button>
        </div>
    )
}

I really enjoyed doing this app, but it took me the whole day truly speaking.

