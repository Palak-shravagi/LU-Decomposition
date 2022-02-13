# LU-Decomposition
-  LU-Decomposition or lower–upper (LU) decomposition is a matrix as the product of a lower triangular matrix and an upper triangular matrix. The product sometimes includes a permutation matrix as well. LU decomposition can be viewed as the matrix form of Gaussian elimination. 

### The LU decomposition of a matrix A is the pair of matrices L and U such that:
 - A = LU
 - L is a lower-triangular matrix with all diagonal entries equal to 1
 - U is an upper-triangular matrix
 ### The properties of the LU decomposition are:
 - The LU decomposition may not exist for a matrix A
 - If the LU decomposition exists then it is unique.
 - The LU decomposition provides an efficient means of solving linear equations.
 - The reason that L has all diagonal entries set to 1 is that this means the LU decomposition is unique. This choice is somewhat arbitrary (we could have decided that U
 must have 1 on the diagonal) but it is the standard choice.
Ex:-AX=B , where A=LU.
    LUX=B, let Y=UX.
    LY=B.
We have to find values of X.

## Steps to run program on google collab
1) Create executable file (%%writefile ludecompose.c) this will be written at the start of program :
2) For compiling follow the commands:
 - %%shell 
 - gcc ludecompose.c -o infile
 - ./infile
