# Simple Python pipeline example

The basic_function.py is the standard way of writing the code, where the function performs everything and returns a result.

The generators.py file uses Python generators to create a composable pipeline. Each generator only performs one function and then we chain them together into a pipeline. The main difference is using the `yield` keyword instead of `return` at the end of each function, which yields a result without exiting the function.