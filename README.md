# JavaScript Loose Comparison Bug

This repository demonstrates a common JavaScript bug related to loose comparison (`==`) and the handling of `null` and `undefined` values.

## Bug Description

JavaScript's loose comparison (`==`) can lead to unexpected results when comparing values, especially when `null` and `undefined` are involved.  This bug highlights a situation where this behavior can cause incorrect logic.

## How to Reproduce

1. Clone this repository.
2. Open `bug.js`.
3. Run the code.  Observe the unexpected result.
4. Open `bugSolution.js` to see a solution that avoids the issue.

## Solution

The solution utilizes strict equality (`===`) to prevent the loose comparison from causing issues. Strict equality ensures that the values are of the same type and have the same value before returning true.