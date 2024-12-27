# Type 'string[]' is not assignable to type 'string'
This repo contains a simple TypeScript program that demonstrates a common type error: assigning a string array to a string variable.
The `greeter` function expects a string argument, but we're passing it a string array.  This leads to a type error.
The solution demonstrates how to correctly handle this situation by either iterating through the array and calling the function multiple times or by modifying the function signature to accept an array of strings.