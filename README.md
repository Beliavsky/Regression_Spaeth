### Regression Spaeth

Code and data files from [John Burkardt](https://people.math.sc.edu/Burkardt/f_src/regression/regression.html) with minor updates. Compile with '''gfortran regression.f90 regression_test.f90'''. Quoting Burkardt's description:

"REGRESSION is a FORTRAN90 library which handles problems in linear regression.

These routines were collected and described by Helmut Spaeth. The most common task for such routines is to solve an overdetermined system of linear equations.

In particular, many routines will produce a least-squares solution. That is, given an M by N matrix A, and an M vector B, the routines will seek an N vector X so which minimizes the L2 norm (square root of the sum of the squares of the components) of the residual


        R = A * X - B
      
The code is in a very provisional state. Many routines have not been carefully proofread or debugged or tested yet."
