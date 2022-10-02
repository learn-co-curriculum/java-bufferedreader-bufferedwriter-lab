# BufferedReader and BufferedWriter Lab

## Learning Goals

- Practice reading and writing a text file using the `BufferedReader` class and
  the `BufferedWriter` class.

## Introduction

Given the `GroceryListDriver` class again, modify the program to use the
`BufferedReader` and `BufferedWriter` classes to read and write a text file.

Reuse the last lab to modify the methods you already wrote to use the new
classes we just learned about.

To implement the reading and writing of a text file, consider the following
instructions and tips:

- Modify the `GroceryListDriver` class.
    - Rewrite the method to write to a text file.
        - Use a `BufferedWriter` object to write out a grocery list.
        - Each item in the list should be on its own new line.
        - Refer back to the BufferedReader and BufferedWriter lesson.
    - Rewrite the method to read a text file line-by-line.
        - Use a `BufferedReader` object to read from the text file.
        - Return a `String` to print out to the console the list of groceries.
        - Refer back to the BufferedReader and BufferedWriter lesson.
- When running the `GroceryListDriver` class, pass in a file named
  `grocery-list.txt`.
- Remove the `@Disabled` annotation from the unit tests and ensure that the
  tests pass successfully. Refactor as needed.
