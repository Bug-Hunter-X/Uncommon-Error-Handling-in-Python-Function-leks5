# Uncommon Error Handling in Python Function

This repository demonstrates an example of uncommon error handling in a Python function.  The function `function_with_uncommon_error` does not raise an error when both inputs are 0. Ideally, this case should be handled more explicitly, perhaps by raising a ZeroDivisionError or returning a specific value to indicate an error condition.

The `bug.py` file contains the function with the unusual behavior. The `bugSolution.py` file provides a solution for better error handling.