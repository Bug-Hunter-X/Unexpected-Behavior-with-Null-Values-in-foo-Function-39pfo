# Unexpected Behavior with Null Values in foo Function

This repository demonstrates a common JavaScript error: unexpected behavior when null values are passed to a function. The function `foo` prematurely exits when null values are provided, which can lead to unpredictable results. The solution file demonstrates how to handle null values appropriately.

## Bug Description
The `foo` function does not gracefully handle null values for `a` or `b`. When either argument is null, the function returns immediately, potentially causing unexpected behavior in the calling code.

## Bug Solution
The improved `foo` function in `bugSolution.js` includes robust null checks. It explicitly handles the cases where either `a` or `b` is null, providing alternative actions or default values to avoid premature termination.

## How to Reproduce the Bug
1. Clone this repository.
2. Run `bug.js` with null values for either `a` or `b`. Observe the function's behavior and its immediate return.
3. Compare the results with the improved function in `bugSolution.js` to see the correct handling of null values.