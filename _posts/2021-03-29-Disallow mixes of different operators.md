---
layout: post
type: "Disallow mixes of different operators"
date: 2021-03-29
---

## Disallow mixes of different operators
Disallow mixes of different operators (no-mixed-operators) Enclosing complex expressions by parentheses clarifies the developer's intention, which makes the code more readable. This rule warns when different operators are used consecutively without parentheses in an expression.Operator precedence determines how operators are parsed concerning each other. Operators with higher precedence become the operands of operators with lower precedence.

## example:

var foo = a && b || c || d;    BAD: Unexpected mix of '&&' and '||'.
var foo = a && b ? c : d;      BAD: Unexpected mix of '&&' and '?:'.
var foo = (a && b) ? c : d;    GOOD
var foo = (a && b) || c || d;  GOOD
var foo = a && (b || c || d);  GOOD

# Examples of incorrect code for this rule:
var foo = a && b < 0 || c > 0 || d + 1 === 0;
var foo = a + b * c;

# Examples of correct code for this rule:
var foo = a || b || c;
var foo = a && b && c;
var foo = (a && b < 0) || c > 0 || d + 1 === 0;
var foo = a && (b < 0 || c > 0 || d + 1 === 0);
var foo = a + (b * c);
var foo = (a + b) * c;