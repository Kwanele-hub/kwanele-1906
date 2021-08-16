---
layout: post
type: "How to serve an HTML file"
date: 2021-08-16
---

## API's and Microservives
# How to serve an Html file

app.get("/", function(req, res) {
  res.sendFile(__dirname + '/views/index.html');
});