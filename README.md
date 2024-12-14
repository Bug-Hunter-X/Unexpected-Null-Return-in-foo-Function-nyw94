# Unexpected Null Return in foo Function

This repository demonstrates a common JavaScript error: unexpected null returns when null values are passed to a function. The function `foo` is designed to add two numbers, but it returns `null` if either input is `null`.  This behavior might not be intuitive or desirable in all situations.

The `bug.js` file contains the buggy code, while `bugSolution.js` provides a possible solution.  The solution offers a more robust approach to handling null inputs by returning 0 in case of null values.

## How to reproduce

1. Clone this repository.
2. Run the `bug.js` file in a JavaScript environment (e.g., node.js).
3. Observe the unexpected output when null values are passed to `foo`.

## Solution

The solution involves modifying `foo` to explicitly check for `null` values and return 0 when encountered. This provides a more predictable and controlled response, preventing potential errors or unexpected behavior in the calling code.