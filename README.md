# Missing Argument Label in Swift Function Call

This example demonstrates a common error in Swift: forgetting to include argument labels when calling a function.

## The Bug

In Swift, functions often use argument labels to improve code readability.  When calling a function, you must provide these labels unless they're explicitly omitted using underscores in the function definition.  Forgetting to include an argument label leads to a compiler error.

## The Solution

Always include the argument labels in function calls unless the function definition uses underscores to omit them. Refer to the `bugSolution.swift` file for the correct implementation.
