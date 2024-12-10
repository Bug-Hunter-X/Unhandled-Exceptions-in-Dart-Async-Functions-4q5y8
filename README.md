# Unhandled Exceptions in Dart Async Functions

This example demonstrates a subtle bug related to exception handling within asynchronous functions in Dart.  Failure to re-throw exceptions can lead to silent failures and make debugging difficult.

The `bug.dart` file contains the flawed code, while `bugSolution.dart` presents the corrected version.  The key difference lies in the use of `rethrow` within the `catch` block. 

This repository serves as a concise illustration of this common Dart coding pitfall and offers a practical solution.