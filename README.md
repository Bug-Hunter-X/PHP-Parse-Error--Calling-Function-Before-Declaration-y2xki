# PHP Parse Error: Calling Function Before Declaration

This repository demonstrates a common PHP error: calling a function before it's declared.  This typically leads to a parse error, particularly when `declare(strict_types=1);` is used.

The `bug.php` file shows the erroneous code. The `bugSolution.php` file provides the corrected version. This simple example highlights the importance of proper function declaration order in PHP.

## How to Reproduce

1. Clone this repository.
2. Run `bug.php` using a PHP interpreter. Observe the parse error.
3. Run `bugSolution.php`. This should execute without errors.