# README Audit

## README Fact-Check Table

| Claim Made in README | True? | Evidence / Correction Made |
|---|---|---|
| Program generates Fibonacci numbers | Yes | The program calculates the next value using `next = a + b`. |
| Program calculates factorial | No | No factorial logic exists in `fibonacci.py`. Claim should be removed. |
| Program takes a number from the user | No | `n = 10` is hard-coded. There is no `input()` function. |
| Program accepts terminal input | No | No user-input functionality is implemented. |
| Program generates 10 Fibonacci numbers | Yes | `n = 10` and `for i in range(n)` cause 10 iterations. |
| Program can generate any number of terms entered by the user | No | The user cannot enter a value. The number of terms must be changed directly in the source code. |
| Program starts with 0 and 1 | Yes | The code initializes `a = 0` and `b = 1`. |
| Program uses a `for` loop | Yes | The Fibonacci sequence is generated using `for i in range(n)`. |
| Program uses addition to generate the next number | Yes | `next = a + b` adds the previous two values. |
| Program updates the Fibonacci sequence | Yes | `a = b` and `b = next` update the values after each iteration. |
| Program prints each Fibonacci number | Yes | `print(a, end=" ")` prints the current Fibonacci value. |
| Program prints the sequence on one line | Yes | `end=" "` keeps the output on the same line. |
| Output is `0 1 1 2 3 5 8 13 21 34` | Yes | These are the values produced during the 10 iterations. |
| Python 3 is required | Yes | The project is a Python script that can be executed with Python 3. |
| NumPy is required | No | No NumPy or other external library is imported. |
| External Python packages are required | No | The program uses only Python's built-in functionality. |
| `requirements.txt` is required | No | There are no external dependencies, so a requirements file is unnecessary. |
| `pip install -r requirements.txt` is required | No | No packages need to be installed. This instruction should be removed. |
| Program validates user input | No | There is no user input or validation logic. |
| Program handles invalid input | No | No input handling or `try/except` logic exists. |
| Program has error handling | No | The program contains no explicit error-handling logic. |
| Program uses an iterative approach | Yes | The sequence is generated using a `for` loop rather than recursion. |
| Program has configurable number of terms | Partially | `n` can be manually changed in the source code, but it cannot be entered by the user. |
| Project uses an MIT License | No | No `LICENSE` file is provided. The README should not claim an MIT License unless one is added. |
| Project contains a Fibonacci generator | Yes | `fibonacci.py` generates and prints the first 10 Fibonacci numbers. |
| Installation requires additional dependencies | No | No external dependencies are used. |
| The project contains `fibonacci.py` | Yes | The uploaded Python source contains the Fibonacci implementation. |
