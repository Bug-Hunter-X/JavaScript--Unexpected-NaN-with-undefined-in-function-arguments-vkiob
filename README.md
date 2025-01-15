# JavaScript: Unexpected NaN with undefined in function arguments

This example demonstrates unexpected behavior in JavaScript when using `undefined` and `null` values as function arguments. Specifically, when using the + operator, null is treated as 0, whereas undefined results in NaN (Not a Number).

## Bug
The `foo` function simply adds two numbers.  However, the output for `undefined` is unexpected.

## Solution
Explicitly handle undefined values using a conditional check or a default value to prevent NaN.