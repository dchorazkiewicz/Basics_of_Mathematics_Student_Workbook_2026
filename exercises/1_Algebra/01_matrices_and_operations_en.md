# Matrices and Basic Operations

## Goal of the Set

After completing this set, the student should understand what a matrix is, when basic operations can be performed, how matrix multiplication and matrix-vector multiplication work, and how matrices describe simple linear transformations.

The goal is not to perform many similar calculations. Each exercise presents a different aspect of working with matrices.

## How to Work Through the Exercises

For each exercise, prepare a solution containing at least:

- the result,
- the main steps,
- a brief explanation of the property or method used,
- a mathematical verification of the result, when possible.

---

## Basic Exercises

### Exercise 1. Matrix Size and Entries
Given
$$A=\begin{pmatrix}2&-1&3\\0&4&5\end{pmatrix},\qquad B=\begin{pmatrix}1&0\\-2&3\\4&1\end{pmatrix}.$$

1. State the sizes of matrices $A$ and $B$.
2. Read off the entries $a_{12}$, $a_{23}$, $b_{21}$, and $b_{32}$.
3. Write the second row of $A$ and the first column of $B$ as vectors.

> **Why this exercise:** builds basic fluency with matrix notation, indices, rows, and columns.

### Exercise 2. Addition and Scalar Multiplication
For
$$A=\begin{pmatrix}1&2\\-1&3\end{pmatrix},\qquad B=\begin{pmatrix}4&-2\\0&5\end{pmatrix}$$
compute
$$A+B,\qquad A-B,\qquad 3A-2B.$$
Explain why matrix addition is possible only for matrices of the same size.

> **Why this exercise:** reinforces entry-by-entry operations and the importance of compatible dimensions.

### Exercise 3. When Can Matrices Be Multiplied?
The matrix sizes are
$$A_{2\times3},\qquad B_{3\times4},\qquad C_{4\times2},\qquad D_{2\times2}.$$
For the products
$$AB,\ BA,\ BC,\ CB,\ AC,\ CA,\ AD,\ DA$$
determine whether they are defined. If so, state the size of the result. Justify each decision using the dimension compatibility condition.

> **Why this exercise:** forces an understanding of dimension compatibility before carrying out any calculation.

### Exercise 4. Matrix Multiplication and Noncommutativity
For
$$A=\begin{pmatrix}1&2\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}2&0\\3&1\end{pmatrix}$$
compute $AB$ and $BA$. Is $AB=BA$? Use this example to explain what noncommutativity of matrix multiplication means.

> **Why this exercise:** shows one of the most important differences between matrix multiplication and multiplication of numbers.

### Exercise 5. Matrix Times Vector
Let
$$A=\begin{pmatrix}2&-1\\1&3\end{pmatrix},\qquad x=\begin{pmatrix}4\\2\end{pmatrix}.$$
Compute $Ax$. Then express $Ax$ as a linear combination of the columns of $A$, with coefficients coming from the vector $x$.

> **Why this exercise:** shows that multiplying a matrix by a vector can be understood as a linear combination of the matrix columns.

### Exercise 6. Transpose
For
$$A=\begin{pmatrix}1&2&3\\4&5&6\end{pmatrix},\qquad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix}$$
compute $A^T$, $B^T$, and $AB$. Then verify in this example that
$$(AB)^T=B^TA^T.$$

> **Why this exercise:** teaches transposition and an important property that reverses the order of factors.

### Exercise 7. Identity Matrix, Zero Matrix, and Powers
For
$$A=\begin{pmatrix}2&1\\0&2\end{pmatrix}$$
compute
$$AI,\qquad IA,\qquad A+0,\qquad A^2,\qquad A^3.$$
Explain the roles of the matrices $I$ and $0$, and describe the pattern you observe in successive powers of $A$.

> **Why this exercise:** organizes the roles of neutral elements and reveals regularity in successive powers of a matrix.

### Exercise 8. Row Operations and Their Reversibility
For
$$A=\begin{pmatrix}1&2&-1\\2&4&1\\-1&1&3\end{pmatrix}$$
perform, in order:
1. $R_2\leftarrow R_2-2R_1$,
2. $R_3\leftarrow R_3+R_1$,
3. interchange $R_2$ and $R_3$.

Write the matrix after each step. Then, for each of the three operations, state an operation that reverses it.

> **Why this exercise:** prepares for elimination by showing that row operations are controlled and reversible transformations of a matrix.

### Exercise 9. Composing Transformations
Let
$$S=\begin{pmatrix}2&0\\0&1\end{pmatrix},\qquad R=\begin{pmatrix}0&-1\\1&0\end{pmatrix}.$$
The matrix $S$ describes nonuniform scaling, while $R$ describes a $90^\circ$ counterclockwise rotation.
For
$$x=\begin{pmatrix}1\\2\end{pmatrix}$$
compute $RSx$ and $SRx$. Compare the results and explain geometrically why the order of these transformations matters.

> **Why this exercise:** interprets matrix multiplication as composition of transformations.

### Exercise 10. Columns of a Matrix Product
Given
$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\qquad B=\begin{pmatrix}1&2\\-1&0\\3&1\end{pmatrix}.$$
Denote the columns of $B$ by $b_1,b_2$.

1. Compute $Ab_1$ and $Ab_2$.
2. Compute the matrix $AB$.
3. Compare the results and explain why the columns of $AB$ are exactly the vectors $Ab_1$ and $Ab_2$.

> **Why this exercise:** extends the interpretation of matrix-vector multiplication to a full product of two matrices instead of simply repeating another $Ax$ exercise.

---

## More Challenging Exercises

### Exercise 11. When Do Matrices Commute?
Given
$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix},\qquad B=\begin{pmatrix}a&b\\c&d\end{pmatrix}.$$
Find the conditions on $a,b,c,d$ under which $AB=BA$. Describe the general form of all such matrices $B$.

> **Why this exercise:** deepens the idea of noncommutativity by finding the conditions under which commutativity does hold.

### Exercise 12. Formula for a Matrix Power
Let
$$A=\begin{pmatrix}1&1\\0&1\end{pmatrix}.$$
Compute $A^2$, $A^3$, and $A^4$, and use them to formulate a conjecture for $A^n$. Then do not stop after checking one more case: assume the formula is true for $n$, multiply by $A$, and explain why you obtain exactly the formula for $n+1$.

> **Why this exercise:** teaches how to recognize a pattern and formulate a generalization from several computations.

### Exercise 13. A Recurrence Written in Matrix Form
Let
$$F=\begin{pmatrix}1&1\\1&0\end{pmatrix}.$$
Compute $F^2$, $F^3$, $F^4$, and $F^5$. Compare the numbers obtained with the sequence
$$0,1,1,2,3,5,8,\ldots$$
and describe the relationship you observe. Then compute
$$F\begin{pmatrix}a\\b\end{pmatrix}$$
and explain how this multiplication performs one recurrence step: it creates the sum of two consecutive terms and keeps one of them for the next step.

> **Why this exercise:** shows the connection between matrix powers and a simple numerical recurrence.

### Exercise 14. Rotation Matrices
The matrix for a rotation through an angle $\theta$ is
$$R(\theta)=\begin{pmatrix}\cos\theta&-\sin\theta\\\sin\theta&\cos\theta\end{pmatrix}.$$
Compute $R(\alpha)R(\beta)$ and, using the angle-sum formulas for sine and cosine, show that
$$R(\alpha)R(\beta)=R(\alpha+\beta).$$
Explain the result geometrically.

> **Why this exercise:** shows the consistency between matrix algebra and the geometry of composing rotations.

### Exercise 15. Associativity of Multiplication and Different Calculation Paths
Given
$$A=\begin{pmatrix}1&2&0\\0&1&1\end{pmatrix},\quad B=\begin{pmatrix}1&0\\2&1\\-1&3\end{pmatrix},\quad C=\begin{pmatrix}2&1\\0&-1\end{pmatrix}.$$
Compute $(AB)C$ and $A(BC)$. Compare the results and the number of intermediate operations. Explain what associativity of matrix multiplication means in this example.

> **Why this exercise:** reinforces associativity by comparing two mathematically equivalent calculation paths.
