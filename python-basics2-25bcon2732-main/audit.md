
# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program calculates the Fibonacci series | Yes | The code prints Fibonacci numbers using `print(a, end=" ")` and updates the values in each iteration. |
| Program calculates the Fibonacci series for a user-entered number of terms | No | `n = 10` is fixed in the code. No user input is taken. Claim corrected. |
| Program accepts input from the terminal | No | There is no `input()` function in the program. Claim deleted. |
| Program can generate a custom number of Fibonacci terms | No | The current program generates exactly 10 terms because `n = 10` is hardcoded. Claim corrected. |
| Program validates the number of terms | No | There are no validation conditions in the code. Claim deleted. |
| Program handles invalid input | No | The program does not accept user input and contains no `try/except` handling. Claim deleted. |
| Python 3 is required | Yes | The code is compatible with Python 3 and can be executed as a Python script. |
| External Python libraries are required | No | There are no import statements. No external packages are required. |
| Program can be run using `python fibonacci.py` | Yes | The code can be saved as `fibonacci.py` and executed using Python, provided it is installed and configured. |
| Program can be run using `python3 fibonacci.py` | Yes | The same Python script can be executed with the `python3` command where it is available. |
| Program asks the user to enter the number of terms | No | The value is assigned directly using `n = 10`. There is no input prompt. Claim deleted. |
| Output for 10 terms is `0 1 1 2 3 5 8 13 21 34` | Yes | The loop executes 10 times and prints the first 10 Fibonacci numbers. |
| Program uses a loop | Yes | The code uses `for i in range(n)` to generate 10 Fibonacci numbers. |
| Program uses addition to calculate the next Fibonacci number | Yes | `next = a + b` adds the previous two values to calculate the next number. |
| Initial Fibonacci values are `0` and `1` | Yes | The code initializes the variables using `a = 0` and `b = 1`. |
| Program updates values to generate successive Fibonacci numbers | Yes | `a = b` and `b = next` update the values in every iteration. |
| Program uses external Python libraries | No | No libraries are imported. The program uses basic Python operations and built-in functions. |
| Repository contains both `fibonacci.py` and `README.md` | Cannot Be Verified | The provided code does not establish which files exist in the repository. |
| Project uses the MIT License | Cannot Be Verified | The code contains no licensing information. The repository's `LICENSE` file must be checked before confirming this claim. |
| README identifies the correct project author | Cannot Be Verified | The code does not contain author information. The author name must be verified separately. |
| Project contains a Fibonacci series generator | Yes | The code generates and prints the first 10 Fibonacci numbers using a loop and arithmetic operations. |
