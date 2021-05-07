---
layout: post
type: "JSON APIs and AJAX"
date: 2021-05-07
---

JSON API's is when updating and storing data.The JSON:API community has created a collection of extensions that APIs can use to provide clients with information or functionality beyond that described in the base JSON:API specification. These extensions are called profiles.

AJAX is the process of sending and recieving data on the url without reloading page. It read data from a web server - after the page has loaded. Update a web page without reloading the page. Send data to a web server - in the background.AJAX = Asynchronous JavaScript And XML. AJAX is not a programming language. AJAX just uses a combination of:
A browser built-in XMLHttpRequest object (to request data from a web server)
JavaScript and HTML DOM (to display or use the data)
AJAX is a misleading name. AJAX applications might use XML to transport data, but it is equally common to transport data as plain text or JSON text.
AJAX allows web pages to be updated asynchronously by exchanging data with a web server behind the scenes. This means that it is possible to update parts of a web page, without reloading the whole page.

Today I even tried how to send data using ajax:
##how to recieve data

var ourRequest = new XMLHttpRequest();
ourRequest.open('GET','file:///home/tcg/my-workspace/practice/json.js');
ourRequest.onload = function(){
    var ourData = JSON.parse(ourRequest.responseText);
    console.log(ourData[0]);
};
ourRequest.send();