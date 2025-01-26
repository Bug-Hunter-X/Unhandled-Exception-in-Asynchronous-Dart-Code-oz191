# Unhandled Exception in Asynchronous Dart Code

This repository demonstrates a common error in Dart: unhandled exceptions within asynchronous operations.  The `bug.dart` file showcases code that could throw an exception during a network request.  The `bugSolution.dart` file provides a corrected version with robust exception handling.

## Problem

Asynchronous operations (like network requests) can fail. If exceptions aren't handled properly, the application might crash silently or behave unexpectedly.  The initial example lacks comprehensive error handling.

## Solution

The solution utilizes `try-catch` blocks to gracefully handle potential errors during the asynchronous `fetchData` function.  This prevents crashes and allows for more controlled error handling and reporting.