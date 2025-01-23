# JavaScript Type Coercion Bug

This repository demonstrates a common JavaScript bug related to type coercion in arithmetic operations.  When adding a number and a string, JavaScript concatenates them instead of performing numerical addition.  The `bug.js` file shows the problem, and `bugSolution.js` provides a solution.

## Bug Description
JavaScript's dynamic typing can be advantageous, but it can also lead to unexpected results. The example shows that when a number is added to a string, the result is the string concatenation of the number and the string, rather than the numerical sum. This is due to JavaScript's implicit type coercion. 

## Solution
Explicit type conversion to numbers before the operation using `parseInt()` or `Number()` will resolve this issue.