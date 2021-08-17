---
layout: post
type: "Express.js"
date: 2021-08-17
---
# Express.js
Express is a Node.js Web Framework.
Node.js is a tool for building networking services and applications.
Express builds on top of its features to provide easy to use functionality that satisfy the needs
of the Web Server use case.
It's Open Source and has lots and lots of pre-built
packages you can just drop in and use.

## Express web server code

const express = require('express')
const app = express()

app.get('/',(req, res)=> res.send());
app.listen(3000, => console.log());