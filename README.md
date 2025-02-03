# JavaScript Function: Unexpected Behavior with Undefined Values

This repository demonstrates a common JavaScript bug related to handling undefined values in a function. The original `foo` function handles `null` values correctly but fails to explicitly handle `undefined` values which can lead to unexpected results. The solution demonstrates how to explicitly check for and handle `undefined` values to prevent this issue.

## Bug

The `bug.js` file contains the original function which correctly handles `null` values, but it doesn't explicitly handle the `undefined` values. 

## Solution

The `bugSolution.js` file demonstrates the improved solution explicitly checking for both `null` and `undefined` values which gives a more robust function. 