# Loose Equality Bug in JavaScript

This repository demonstrates a common error in JavaScript related to loose equality (==) when dealing with null and undefined values.

The `bug.js` file contains a function `foo` that uses loose equality to check if a value is null.  This leads to unexpected behavior when the input is `undefined`.

The `bugSolution.js` file shows the corrected version, using strict equality (===) to correctly handle null and undefined values.

## How to reproduce

1. Clone this repository.
2. Run `node bug.js` to see the unexpected NaN result.
3. Run `node bugSolution.js` to see the corrected behavior.