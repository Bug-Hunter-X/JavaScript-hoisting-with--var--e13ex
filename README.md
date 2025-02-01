# JavaScript Hoisting with 'var'

This repository demonstrates a common JavaScript issue related to hoisting and the `var` keyword.  When you use `var` to declare a variable, JavaScript hoists the declaration to the top of its scope, but it doesn't initialize the variable.  This can lead to unexpected `undefined` values.

## The Bug

The `bug.js` file contains a function that attempts to access a variable before it's declared and assigned a value.

## The Solution

The `bugSolution.js` file shows how to avoid this problem by ensuring variables are declared and initialized before they are accessed.  Using `let` or `const` instead of `var` helps because they prevent hoisting in the same manner.

## How to reproduce

1. Clone the repository.
2. Run `bug.js` in a JavaScript environment (e.g., Node.js, browser console).
3. Observe the output ('undefined').
4. Run `bugSolution.js` in a JavaScript environment and compare the output.