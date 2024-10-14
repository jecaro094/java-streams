# Using Java Streams (Pluralsight course)

## Insights
- We are not allowed to process the same stream twice.
  - We will get an error when we run the code.
- Remember that `try with resources` is the closest to the `context manager` used in Python.    
- Streams are only computed in the `reduce` step. Because of that, they are way more efficient than copying objects in the middle to get the final result, in the same way that we could use collections or things like that.
- When we apply a `reduction`, we consider the `Optional` to consider the reduction of empty streams as 0.

## What is this repository about?
- Different uses of streams in java code.
- How to define streams from arrays.
- How to refactor for loops to streams.
- How to read and close files using streams (using `try with resources` strategy).
- Learn how to handle `Optionals` in streams.
- Put stream data in collectors; mutable objects to handle data in an efficient way.