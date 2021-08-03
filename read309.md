## What is functional programming?
a programming paradigm — a style of building the structure and elements of computer programs — that treats computation as the evaluation of mathematical functions and avoids changing-state and mutable
## What is a pure function and how do we know if something is a pure function?
- It returns the same result if given the same arguments (it is also referred as deterministic)
- It does not cause any observable side effects
- Reading Files
If our function reads external files, it’s not a pure function — the file’s contents can change.
- Random number generation
Any function that relies on a random number generator cannot be pure.
## What are the benefits of a pure function?
- easier to reason about.
- easier to combine.
- easier to test.
- easier to debug.
- easier to parallelize.
## What is immutability?
Unchanging over time or unable to be changed.
## What is Referential transparency?
This pure function will always have the same output, given the same input.

