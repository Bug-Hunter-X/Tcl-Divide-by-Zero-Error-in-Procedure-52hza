# Tcl Divide-by-Zero Bug

This repository demonstrates a common error in Tcl: the accidental divide-by-zero.  The `bug.tcl` file contains a procedure that does not handle the case where the divisor is zero. The `bugSolution.tcl` provides a corrected version.

## How to reproduce the error:

1.  Run `bug.tcl`.
2. Observe the error message indicating division by zero.

## How to fix the error:

The solution involves adding error handling. The provided solution demonstrates a way to gracefully handle this type of error by checking for zero as the divisor before performing the division. 
