# IndexError in Dart List Access

This repository demonstrates a common error in Dart: the `IndexError`.  This error occurs when you try to access an element in a list using an index that is outside the valid range of indices for that list.  Lists in Dart are zero-indexed, meaning the first element is at index 0.

The `bug.dart` file contains code that produces the `IndexError`. The `bugSolution.dart` file provides a solution to avoid this error by checking the index bounds before accessing the element.

## How to reproduce the error

1. Clone this repository.
2. Open `bug.dart` in your Dart editor.
3. Run the code.  You will see an `IndexError` exception.

## Solution

The solution involves checking the index before accessing the list element, using a method like `list.length` to determine if the index is valid.