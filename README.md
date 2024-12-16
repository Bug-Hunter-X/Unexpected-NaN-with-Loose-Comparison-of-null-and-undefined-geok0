# Unexpected NaN with Loose Comparison of null and undefined

This repository demonstrates a common JavaScript error related to loose comparison (==) of null and undefined values.  The function `foo` handles null correctly but produces NaN when called with undefined because of the loose comparison.

The solution demonstrates how to use strict equality (===) to handle null and undefined separately and avoid the NaN issue.

## How to reproduce
1. Clone this repository.
2. Run `node bug.js` to see the unexpected NaN output.
3. Run `node bugSolution.js` to see the corrected output.