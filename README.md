# Haskell Undefined Value Error

This repository demonstrates a common error in Haskell programming: attempting to use an undefined value. The `bug.hs` file contains the erroneous code, while `bugSolution.hs` provides a corrected version.

The error arises from trying to perform arithmetic operations on a value that has not been assigned a concrete value.  This results in a runtime exception.

The solution involves proper initialization or handling of potentially undefined values using pattern matching, maybe monad or other error handling techniques.