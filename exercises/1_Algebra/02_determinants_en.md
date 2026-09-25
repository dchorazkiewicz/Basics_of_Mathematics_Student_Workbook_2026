# Determinants

## Goal of the Set

After completing this set, the student should be able to compute determinants of small matrices, understand their connection with invertibility, know how row operations affect the determinant, and recognize situations in which the determinant gives quick information about a matrix or a system of equations.

## Basic Exercises

### Exercise 1. Determinant of a 2×2 Matrix
Compute
$$\det\begin{pmatrix}3&-2\\5&4\end{pmatrix},\qquad \det\begin{pmatrix}1&7\\2&14\end{pmatrix}.$$
Which matrix is invertible? Justify your answer.

> **Why this exercise:** introduces the simplest determinant calculation and immediately connects it with invertibility.

### Exercise 2. Determinant of a 3×3 Matrix
For
$$A=\begin{pmatrix}1&2&-1\\0&3&4\\2&1&5\end{pmatrix}$$
compute $\det A$ using Sarrus' rule. Then perform one simple check using a chosen property of the determinant.

> **Why this exercise:** teaches a basic method for $3\times3$ matrices and builds the habit of checking the result without adding a second full solution.

### Exercise 3. Swapping Two Rows
For
$$A=\begin{pmatrix}1&2&0\\0&3&1\\2&1&1\end{pmatrix}$$
compute $\det A$. Then form a matrix $B$ by swapping the first and second rows of $A$.

First predict $\det B$ using a determinant property, and then verify your prediction by calculation.

> **Why this exercise:** gives a second classical calculation with a $3\times3$ determinant while teaching the precise effect of a row swap on the sign of the determinant.

### Exercise 4. Triangular Matrix
Without expanding the determinant, compute
$$\det\begin{pmatrix}2&4&1\\0&-3&5\\0&0&7\end{pmatrix}.$$
State the rule for an arbitrary triangular matrix and explain it using this example.

> **Why this exercise:** reinforces an important property of triangular matrices.

### Exercise 5. Row Operations
For
$$A=\begin{pmatrix}1&2&3\\2&1&0\\-1&4&2\end{pmatrix}$$
find $\det A$ by simplifying the matrix with row operations. At each step, indicate whether and how the determinant changes.

> **Why this exercise:** connects determinants with row operations and requires conscious tracking of every step.

### Exercise 6. Parameter and Invertibility
For
$$A(t)=\begin{pmatrix}t&1\\2&t\end{pmatrix}$$
find all values of $t$ for which the matrix is not invertible. Explain how your answer is related to the determinant being zero.

> **Why this exercise:** shows how the determinant can be used to study a family of matrices depending on a parameter.

### Exercise 7. Using Properties Instead of Recomputing
Suppose that for a $3\times3$ matrix, $\det A=-4$. Compute
$$\det(2A),\qquad \det(A^T),\qquad \det(A^2),\qquad \det(-A).$$
Justify each answer using the appropriate property.

> **Why this exercise:** teaches how to use determinant properties instead of repeating a full calculation.

### Exercise 8. Determinant of a Product
Let $A,B$ be square matrices such that $\det A=3$ and $\det B=-5$. Compute $\det(AB)$, $\det(BA)$ and, if it exists, $\det(A^{-1}B)$. Explain why the first two results are equal even though usually $AB\neq BA$.

> **Why this exercise:** organizes how determinants behave with respect to products and inverses.

### Exercise 9. Area and the Determinant
The vectors
$$u=\begin{pmatrix}3\\1\end{pmatrix},\qquad v=\begin{pmatrix}1\\4\end{pmatrix}$$
span a parallelogram. Compute its area using a determinant. Then reverse the order of the vectors and explain what changes in the determinant and what does not change in the area.

> **Why this exercise:** gives the determinant a geometric interpretation and distinguishes its sign from the value of the area.

### Exercise 10. Detecting Dependence
Without carrying out a full determinant calculation, explain why
$$\det\begin{pmatrix}1&2&3\\2&4&6\\0&1&5\end{pmatrix}=0.$$
Identify a specific dependence between the rows and connect it with noninvertibility of the matrix.

> **Why this exercise:** teaches how to recognize a zero determinant from the structure of a matrix.

## More Challenging Exercises

### Exercise 11. Shortening the Calculation with Row Operations
Compute
$$\det\begin{pmatrix}1&2&3\\1&3&4\\1&4&6\end{pmatrix}$$
by first performing row operations that create as many zeros as possible. State which operations do not change the determinant.

> **Why this exercise:** develops planning instead of mechanically repeating the same procedure.

### Exercise 12. A Parameter Revealed by a Row Operation
For
$$A(t)=\begin{pmatrix}1&2&3\\2&4&t\\0&1&1\end{pmatrix}$$
find the values of $t$ for which the matrix is not invertible.

Before computing the determinant, perform the operation
$$R_2\leftarrow R_2-2R_1$$
and use the resulting structure. At the end, explain what special thing happens to the rows for the value of the parameter you found.

> **Why this exercise:** combines a parameter, row operations, and recognition of dependence in one short argument.

### Exercise 13. Determinant by Elimination
Compute the determinant
$$A=\begin{pmatrix}1&2&3\\2&5&7\\1&0&2\end{pmatrix}$$
using elimination. Record the effect of every row operation used on the value of the determinant.

> **Why this exercise:** reinforces organizing a determinant calculation through row operations without introducing an unnecessary second procedure.

### Exercise 14. A System of Equations and the Determinant
Consider the system $Ax=b$, where
$$A=\begin{pmatrix}1&2\\k&4\end{pmatrix}.$$
For which values of $k$ does the system have exactly one solution for every $b$? For the remaining value, give an example of a right-hand side $b$ for which the system has infinitely many solutions, and an example for which it has no solution.

> **Why this exercise:** connects the determinant with uniqueness of solutions and requires distinguishing the exceptional cases.

### Exercise 15. Combining Determinant Properties
Let $A$ and $B$ be invertible $2\times2$ matrices with
$$\det A=-2,\qquad \det B=3.$$
Without finding the entries of the matrices, compute
$$\det\left(B^{-1}A^TB\right).$$
State the determinant properties you use in order and explain why the factors involving $B$ eventually cancel.

> **Why this exercise:** tests the transfer of several known properties into one short problem instead of checking a single property again with numbers.
