# README Audit

## README Fact-Check Table

### Factorial Program

| Claim Made in README                                        | True?                        | Evidence / Correction Made                                                                       |
| ----------------------------------------------------------- | ---------------------------- | ------------------------------------------------------------------------------------------------ |
| Program calculates factorial                                | Yes                          | `fact` is multiplied by each value inside the `for` loop.                                        |
| Program calculates factorial of a user-entered number       | Yes                          | `n = int(input("Enter a number: "))` accepts a number from the user.                             |
| Program accepts input from the terminal                     | Yes                          | The program uses the `input()` function.                                                         |
| Program calculates factorial for non-negative integer input | Yes                          | The loop calculates the factorial for non-negative integer input.                                |
| Program validates negative numbers                          | No                           | There is no condition to check whether `n` is negative.                                          |
| Program handles non-numeric input                           | No                           | There is no `try/except` block to handle invalid input.                                          |
| Python 3 is required                                        | Yes                          | The program is a Python script that can be run using Python 3.                                   |
| NumPy is required                                           | No                           | There is no `import numpy` statement. NumPy is not used.                                         |
| `requirements.txt` is required                              | No                           | The program does not require external packages.                                                  |
| Program can be run using `python factorial.py`              | Yes, if the filename matches | The command must match the actual filename in the repository.                                    |
| Program displays `Enter a number:`                          | Yes                          | The code contains `input("Enter a number: ")`.                                                   |
| Output is `Factorial = 120` when the input is `5`           | Yes                          | `5 × 4 × 3 × 2 × 1 = 120`.                                                                       |
| Program uses a loop                                         | Yes                          | The code uses `for i in range(1, n + 1)`.                                                        |
| Program uses multiplication to calculate factorial          | Yes                          | `fact = fact * i` performs repeated multiplication.                                              |
| Initial factorial value is `1`                              | Yes                          | The code contains `fact = 1`.                                                                    |
| Program has input validation                                | No                           | No validation conditions exist.                                                                  |
| Program has error handling                                  | No                           | No `try`, `except`, or other error-handling logic exists.                                        |
| Program uses external Python libraries                      | No                           | No external libraries are imported.                                                              |
| Project uses MIT License                                    | Not verified                 | A license claim should only be included if the repository contains the appropriate license file. |
| `pip install -r requirements.txt` is necessary              | No                           | No external packages are required.                                                               |

### Fibonacci Program

| Claim Made in README                                                        | True?                        | Evidence / Correction Made                                                   |
| --------------------------------------------------------------------------- | ---------------------------- | ---------------------------------------------------------------------------- |
| Program generates the Fibonacci series                                      | Yes                          | The program generates Fibonacci numbers using the variables `a` and `b`.     |
| Program accepts the number of terms from the user                           | Yes                          | `n = int(input("Enter the number of terms: "))` accepts the number of terms. |
| Program starts the series with `0` and `1`                                  | Yes                          | The code initializes the variables using `a, b = 0, 1`.                      |
| Program uses a loop                                                         | Yes                          | The code uses `for i in range(n)`.                                           |
| Program updates Fibonacci numbers correctly                                 | Yes                          | `a, b = b, a + b` calculates the next pair of values.                        |
| Program prints the requested number of terms for non-negative integer input | Yes                          | The loop runs `n` times for non-negative integer input.                      |
| Output is `0 1 1 2 3 5 8` when the input is `7`                             | Yes                          | The program prints seven Fibonacci terms.                                    |
| Python 3 is required                                                        | Yes                          | The program can be executed using Python 3.                                  |
| Program uses external Python libraries                                      | No                           | No external libraries are imported.                                          |
| Program validates negative numbers                                          | No                           | No condition checks whether the number of terms is negative.                 |
| Program handles non-numeric input                                           | No                           | `int()` raises an error if the input cannot be converted to an integer.      |
| Program has error handling                                                  | No                           | No `try/except` block exists.                                                |
| Program requires `requirements.txt`                                         | No                           | No external dependencies are required.                                       |
| Program can be run using `python fibonacci.py`                              | Yes, if the filename matches | The command must match the actual filename in the repository.                |

### Structure-to-Dictionary Program

| Claim Made in README                                            | True? | Evidence / Correction Made                                                                          |
| --------------------------------------------------------------- | ----- | --------------------------------------------------------------------------------------------------- |
| Program displays student details                                | Yes   | The code prints the student's name, roll number, and marks.                                         |
| Program stores student information in a dictionary              | Yes   | The `student` variable contains the keys `name`, `roll`, and `marks`.                               |
| Student name is Rahul                                           | Yes   | The dictionary contains `"name": "Rahul"`.                                                          |
| Student roll number is 101                                      | Yes   | The dictionary contains `"roll": 101`.                                                              |
| Student marks are 87.5                                          | Yes   | The dictionary contains `"marks": 87.5`.                                                            |
| Program accesses dictionary values using keys                   | Yes   | The code uses `student["name"]`, `student["roll"]`, and `student["marks"]`.                         |
| Program displays the complete dictionary                        | Yes   | The code prints the complete `student` dictionary.                                                  |
| Program creates a Python dictionary                             | Yes   | The dictionary is created directly using a dictionary literal.                                      |
| Program converts an actual C structure into a Python dictionary | No    | The code creates a Python dictionary directly and does not define or convert an actual C structure. |
| Program accepts student information from the user               | No    | Student information is predefined in the code.                                                      |
| Program uses a loop                                             | No    | Student details are printed directly without a loop.                                                |
| Program validates student information                           | No    | No validation conditions exist.                                                                     |
| Program handles invalid input                                   | No    | The program does not accept user input or include error handling.                                   |
| Python 3 is required                                            | Yes   | The program can be executed using Python 3.                                                         |
| Program uses external Python libraries                          | No    | No external libraries are imported.                                                                 |
| Program requires `requirements.txt`                             | No    | No external packages are required.                                                                  |
| Program can be run using `python struct_to_dict.py`             | Yes   | This command matches the filename shown in the repository.                                          |

## Overall Audit Summary

* The factorial program accepts a number from the user and calculates its factorial.
* The Fibonacci program accepts the number of terms and prints the corresponding Fibonacci series.
* The structure-to-dictionary program creates a dictionary containing predefined student information and displays its values.
* All three programs use Python's built-in functionality and do not require external libraries.
* None of the programs includes explicit input validation or exception handling.
* The README should accurately describe the functionality of each program and avoid unsupported claims.
* The structure-to-dictionary program creates a Python dictionary directly rather than converting an existing C structure.
* The run commands should match the actual filenames in the repository.

This audit helps ensure that the README remains accurate, clear, and consistent with the source code.


