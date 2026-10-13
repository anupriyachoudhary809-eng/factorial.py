
# README Audit: Factorial Calculator in Python

## Purpose
This report compares the claims in README.md with the actual code in factorial.py.

## Audit Results

| README Claim | Verdict | Evidence |
|---|---|---|
| Calculates the factorial of an integer entered by the user. | Supported | The program accepts input using `input()` and calculates the factorial using a loop. |
| Install Python 3. | Supported | The file uses Python syntax and built-in functions. |
| Open a terminal in the project folder. | Supported | This is a valid way to run the script. |
| Run `python factorial.py`. | Supported | The command runs the Python script when Python is configured correctly. |
| Enter a non-negative integer. | Supported with qualification | The calculation works for non-negative integer input, but negative values are not rejected. |
| Input `5` produces `Factorial: 120`. | Supported | The loop calculates 120 for input 5. |
| The learning objective covers input, variables, loops, and multiplication. | Supported | The program uses `input()`, variables, a `for` loop, and multiplication assignment. |
| The language is Python. | Supported | The source file contains Python code. |

## Important Observation

All eight README claims are supported for their intended use, with a qualification concerning negative inputs. The program does not validate negative integers or handle invalid input explicitly.

For negative integer input, the loop does not execute and the program prints `Factorial: 1`. The README should clarify that the program is intended for non-negative integers.

## Conclusion

The README accurately describes the program's intended functionality. Future improvements could include input validation and clearer error handling.
