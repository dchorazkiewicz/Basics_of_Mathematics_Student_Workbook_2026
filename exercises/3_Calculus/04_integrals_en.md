# Integrals

## Goal of the Problem Set

The student should understand the indefinite integral as a family of antiderivatives, the definite integral as a tool for summation and area, and should be able to apply the basic techniques: direct integration, simple substitution, and integration by parts.

In the solutions, the result itself is not the only important part. The student should be able to explain **how they recognize the appropriate method**, verify an antiderivative by differentiation, and distinguish the meaning of an indefinite calculation from the interpretation of a definite integral.

## Basic Problems

### Problem 1. Antiderivative and Verification
For
$$f(x)=3x^2-4x+5$$
find one antiderivative $F(x)$. Write the entire family of antiderivatives, verify the result by differentiation, and explain the meaning of the constant $C$.

> **Why this problem:** it introduces integration as the inverse operation to differentiation.

### Problem 2. Powers, Roots, and the Domain
Compute
$$\int\left(2\sqrt{x}+\frac{3}{x^2}-x^{1/3}\right)\,dx.$$
First rewrite the terms as powers, determine the domain of the original expression, and verify the result by differentiation.

> **Why this problem:** it reinforces the power rule and reminds the student to keep track of the domain.

### Problem 3. Recognizing Basic Antiderivatives
Compute
$$\int\left(2e^x+3\cos x-4\sin x\right)\,dx.$$
Match each term with a known derivative and verify the entire result with one differentiation.

> **Why this problem:** it builds a catalogue of basic antiderivatives from known derivatives.

### Problem 4. Substitution as Reversing the Chain Rule
Compute
$$\int 2x(x^2+1)^4\,dx.$$
Before calculating, identify a candidate for the new variable $u$ and show that its derivative appears in the integral. Finally, verify the result by differentiation.

> **Why this problem:** it teaches how to recognize substitution as reversing the chain rule.

### Problem 5. The Same Substitution in a Different Context
Compute
$$\int xe^{x^2}\,dx.$$
First compare the structure with Problem 4 and explain what is common despite the different appearance of the function.

> **Why this problem:** it shows that the substitution mechanism is recognized by structure, not by the type of function.

### Problem 6. When Does a Logarithm Appear from an Integral?
Compute
$$\int\frac{2x}{x^2+5}\,dx.$$
Identify the denominator as a candidate for substitution, compare the numerator with its derivative, and explain the source of the logarithm in the result.

> **Why this problem:** it teaches how to recognize the structure “derivative of the denominator over the denominator.”

### Problem 7. Integration by Parts as Reversing the Product Rule
Compute
$$\int xe^x\,dx.$$
First write the product differentiation rule and, on that basis, explain the meaning of the integration-by-parts formula. Verify the result by differentiation.

> **Why this problem:** it connects a new technique with the familiar product rule.

### Problem 8. Choosing the Factors in Integration by Parts
Compute
$$\int x\cos x\,dx.$$
Before calculating, justify why it is convenient to differentiate $x$ and integrate $\cos x$, rather than the other way around.

> **Why this problem:** it teaches that integration by parts requires a deliberate choice of factors.

### Problem 9. Definite Integral and Geometric Area
Compute
$$\int_{-1}^{2}x\,dx.$$
Then separately compute the areas of the parts of the graph below and above the $x$-axis and explain the difference between the definite integral and geometric area.

> **Why this problem:** it clarifies the difference between signed accumulation and area.

### Problem 10. Definite Integral and Checking the Result
Before carrying out the exact calculation, estimate the possible range of values of the integral
$$\int_0^2(x^2+1)\,dx,$$
using
$$1\le x^2+1\le5$$
on $[0,2]$. Only then compute the integral exactly, compare the result with the earlier estimate, and explain what type of computational error such a check can detect.

> **Why this problem:** it teaches how to predict the possible range of a result and check the calculation.

## More Difficult Problems

### Problem 11. Choose the Method First
For each integral, first write which method you choose and how you recognize it, and then compute:
1. $\int\sin(3x)\,dx$,
2. $\int x\ln x\,dx$,
3. $\int\frac{x}{\sqrt{x^2+1}}\,dx$.

> **Why this problem:** it tests the choice of method based on the structure of the problem.

### Problem 12. Symmetry, Sign, and Absolute Value
Compare
$$\int_{-2}^{2}x\,dx$$
and
$$\int_{-2}^{2}|x|\,dx.$$
Before calculating, predict the results from symmetry and a sketch, then carry out the calculation and explain the difference.

> **Why this problem:** it teaches how to use symmetry and geometry before applying a computational procedure.

### Problem 13. An Integral Depending on the Upper Limit
Let
$$F(x)=\int_0^x(t^2+1)\,dt.$$
Determine $F(x)$, compute $F'(x)$, and compare the result with the integrand. Explain in your own words why the height of the function describes the local rate of increase of the accumulated area.

> **Why this problem:** it connects differentiation and integration through the idea of accumulation.

### Problem 14. A Piecewise-Defined Function
Let
$$f(x)=\begin{cases}x+1,&-1\le x<1,\\2,&1\le x\le3.\end{cases}$$
Sketch the graph, decide where to split the integral, compute
$$\int_{-1}^{3}f(x)\,dx$$
and verify the result geometrically.

> **Why this problem:** it requires understanding the definition of the function before carrying out the calculation.

### Problem 15. Recovering a Function from Its Derivative and a Condition
The function $F$ satisfies
$$F'(x)=2xe^{x^2}$$
and
$$F(0)=3.$$

1. Recognize the method needed to find the function $F$.
2. Determine the entire family of functions with the given derivative.
3. Use the condition $F(0)=3$ to determine the correct constant.
4. Verify the final result by differentiation and substitution of $x=0$.

> **Why this problem:** it combines recognition of substitution, the meaning of the constant of integration, and an initial condition in one problem, using only mechanisms introduced earlier.
