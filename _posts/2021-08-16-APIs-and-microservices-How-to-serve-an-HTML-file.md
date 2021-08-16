---
layout: post
type: "How to serve an HTML file"
date: 2021-08-16
---

# API's and Microservives
## How to serve an Html file

app.get("/", function(req, res) {
  res.sendFile(__dirname + '/views/index.html');
});

## Terminologies
>method is an http method in lowercase 
>path is a relative path on the server
>handler is a function that express calls when the route is matched(function(req, res){...})
>global variable in node are objects that gives scope of entire project.