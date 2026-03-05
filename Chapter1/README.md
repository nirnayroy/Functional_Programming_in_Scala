# What is functional programming?

- Programming with pure functions
- Avoiding mutable state and side effects
- set a restriction on how we write programs and not on what they express
- pure functions have no side effects like mutating data, printing to stdout, writing to file, etc
- pure functions are easier to test, reuse, parallelize, generalize and reason about

**Dependency Injection**
- Function getting its dependency from an external source rather than creating it internally
- Can be useful to define a class as a trait to make it more testable(it the test could be a class that extends the trait)

**Referential Transperency**
- Expressions are any part of the program which can be evaluated to a result
- Referential transparency is a property of expressions, where the expression can be replaced by its result without changing the meaning of the program
- A function is pure if the expression f(x) is referentially transparent for all referentially transparent x.
- e.g. in-place append is not RT