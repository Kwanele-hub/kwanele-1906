---
layout: post
type: "for loop statement"
date: 2020-10-23
---
##for loop statement

the week was long and had back and fords with everything I've been doing, I did my daily exercise.
Moral gave us a weekly task which we had to write pure javascript.
this was my code...

const students = [{name:"Ziphozonke", mark:"25"}, {name:"Siphelele", mark:"34"},
 {name:"Thembelani", mark:"28"},{name:"Kwanele", mark:"40"}, {name:"Yandisa", mark:"45"}]

function displayStudents(students){
let names = students.map((student)=>student.name)
return names
}
console.log(displayStudents(students))
const grades = [25, 34, 28, 40, 45];

function getAvg(grades) {
  const total = grades.reduce((acc, c) => acc + c, 0);
  return total / grades.length;
}

const average = getAvg(grades);
console.log(average);

function topAchieve(students){
  let names = students.map((student) =>student.name)
  return 
};

the time we were doing our verification one of the past students "Sabelo" insisted us to use for-loops,
truly speaking I had no clue on what was happening not until we did multiple times.
I wasn't familiar with loops, but on freeCodeCamp, I've passed them.
that's where I realised that some of the things I should get back and look at them carefully.

for-loop is a control flow statement for specifying iteration, which allows code to be executed repeatedly.
For-loops are typically used when the number of iterations is known before entering the loop.

