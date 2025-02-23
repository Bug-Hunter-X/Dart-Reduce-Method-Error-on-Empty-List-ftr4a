# Dart Reduce Method Error on Empty List
This repository demonstrates a common error encountered when using the `reduce` method in Dart with an empty list. The `reduce` method requires at least one element to perform its operation; attempting to use it on an empty list results in an error.  The solution shows how to handle this scenario gracefully.

## Bug
The `bug.dart` file contains code that attempts to use `reduce` on an empty list, leading to a runtime error.

## Solution
The `bugSolution.dart` file provides a corrected version that checks for an empty list before applying the `reduce` method, preventing the error. This is achieved by using an `if` statement to check if the list is empty.  If it is, a default value or a different approach can be used; otherwise, `reduce` is executed normally.
