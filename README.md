# TypeScript: Handling undefined in string | null parameter

This repository demonstrates a common TypeScript error when dealing with optional parameters that can be either a string or null.  The issue arises when passing `undefined` to a function that accepts `string | null`. While the function explicitly handles `null`, it throws an error for `undefined`.

The `bug.ts` file showcases the error, while `bugSolution.ts` provides a solution.

## How to reproduce the error:
1. Clone this repository.
2. Navigate to the directory.
3. Compile the code using `tsc bug.ts`.
4. Observe the compiler error related to the `undefined` input.

## Solution:
The solution involves explicitly checking for `undefined` either using an `if` statement or optional chaining.  See `bugSolution.ts` for a corrected version.
