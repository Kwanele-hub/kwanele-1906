---
layout: post
type: "javascript recursion"
date: 2021-03-26
---
## Javascript recursion

Recursion is when a function calls by itself.Recursive functions let you perform a unit of work multiple times.
This is exactly what for/while loops let us accomplish!
Sometimes, however, recursive solutions are a more elegant approach to solving a problem.

function that counts down from a given number
1.Take one parameter called number. This is our starting point.
2.Go from number down to 0, logging each one along the way.

function countDownFrom(number) {
	if (number === 0) {
		return;
	}

    console.log(number);    
    countDownFrom(number - 1);
}

countDownFrom(5);