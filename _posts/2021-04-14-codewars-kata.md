---
layout: post
type: "codewars kata"
date: 2021-04-14
---
## codewars kata 8 kyu (drink about)

This kata is all about functions,I suppose to make function that receive age, and return what they drink.


instructions: 

Kids drink toddy.
Teens drink coke.
Young adults drink beer.
Adults drink whisky.

Rules:

Children under 14 old.
Teens under 18 old.
Young under 21 old.
Adults have 21 or more.

Examples: (Input --> Output)

this is my solution:

function peopleWithAgeDrink(old) {
  if (old>=21)return "drink whisky";
  if (old<14)return"drink toddy"
  if (old<18)return"drink coke"
  if (old<21)return"drink beer";
};