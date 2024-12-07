# Unexpected Type Coercion in JavaScript

This repository demonstrates a common JavaScript bug related to unexpected type coercion.  JavaScript's loose typing system can lead to unexpected behavior when performing operations on variables of different types.

The `bug.js` file contains the buggy code. The `bugSolution.js` file provides a corrected version.

## Bug Description

The code attempts to add a number and a string. JavaScript implicitly coerces the number to a string, resulting in string concatenation instead of numerical addition. This can be problematic and lead to unexpected results in calculations.

## Solution

The solution is to ensure that both operands are of the same numeric type before performing the addition.  Explicit type conversion using `parseInt()` or `Number()` can resolve this issue.