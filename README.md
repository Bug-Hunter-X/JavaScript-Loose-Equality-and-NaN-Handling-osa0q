# JavaScript Loose Equality and NaN Handling

This repository demonstrates a common JavaScript bug related to loose equality (`==`) and the handling of `NaN` (Not a Number).

## The Bug
The `foo` function adds two numbers. It attempts to handle `null` values gracefully.  However, it doesn't account for `NaN`, which leads to unexpected behavior.

## The Solution
The corrected version uses strict equality (`===`) for more precise comparisons and includes explicit checks for `NaN` using `isNaN()`.