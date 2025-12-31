# Optimization phases

Where you define Optimization 0, you have to have only constants so that if’s, assigned classes / value types are known statically at compilation or at generating indexes for compilations. Each try catch block must have it’s result known at compilation time, so you cannot do much; variables would rather need to be defined; but if-then can be used freely, as well as loops, as long as they don’t give any exponent complications and resolve in compilation time, with constant limit to complexity of each state or expression within it’s context.

Where you define Optimization 9, you have a dynamic language. While it looks the same, try / catch is ran at runtime; the halting problem, once it would not solve otherwise, would try with higher optimization factors, and get distrubed or tired after 10 or 15 minutes for example, or after some milliseconds for trivial task with some lenghty exceptions.

More intelligent version of halting problem would use the user input availability:

- Does the user see “close” button with explanation or easily access help page to exit with keyboard.
- Is the program ready to process such input.
- If the user won’t halt, does the process have ongoing task, and will this task be marked as “complete”.

While we might not yet have complete solution to Halting problem, you can see that we can give definite solutions:

- Pattern for passing the halting problem
- Assertions to follow this pattern with given control variables, for example having a natural number definitely counting down and completing once it’s zero.