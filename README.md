# Post-increment in printf: Unexpected Output

This example demonstrates a subtle issue related to the post-increment operator (`++`) and the order of evaluation within the `printf` function in C.

The `bug.c` file contains a simple program that initializes an integer variable `x` to 10 and then prints its value twice using `printf`.  The first print statement uses the post-increment operator. The expectation might be that both printf calls print 10 and 11 respectively but this is not necessarily guaranteed.

The solution (`bugSolution.c`) addresses this issue by clarifying the order of evaluation to avoid unintended consequences and improve readability.
