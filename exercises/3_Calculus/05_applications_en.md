# Applications of Differential and Integral Calculus

## Goal of the Problem Set

This problem set is cross-sectional in nature and is intentionally shorter than the others. The student should be able to choose variables from a problem description, build a model, decide whether a derivative, an integral, or both tools are needed, and then interpret the result in the context of the problem.

The problem set may be completed flexibly near the end of the semester. It is not intended to repeat all the calculus from the previous problem sets, but rather to check whether the student can use the methods learned in a problem that does not immediately suggest a ready-made formula.

## Basic Problems

### Problem 1. Motion — from Position to Velocity
The position of a point is described by
$$
s(t)=t^3-6t^2+9t+2,\qquad t\ge0.
$$

1. Determine the velocity and acceleration.
2. Find the times at which the point stops.
3. Determine on which intervals the point moves in the positive direction of the axis and on which intervals it moves in the negative direction.

> **Why this problem:** it shows the derivative as a real rate of change and requires interpretation of the sign of the derivative in the context of motion.

### Problem 2. Maximum Area of a Rectangle
A rectangle has perimeter $40$.

1. Write its area as a function of the length of one side.
2. Determine the domain of this function resulting from the geometry of the problem.
3. Find the dimensions that give the maximum area.
4. Justify that the point found actually gives a maximum.

> **Why this problem:** it teaches the complete optimization scheme: model → domain → derivative → verification and interpretation of the maximum.

### Problem 3. A Box Made from Cardboard
From a $30\text{ cm}\times40\text{ cm}$ sheet, squares of side length $x$ are cut from the corners and the edges are folded up to form an open box.

Write the volume as a function of $x$, determine the physically meaningful domain, and find the value of $x$ for which the volume is greatest.

> **Why this problem:** it develops optimization modeling in a situation where the objective function is not given and must be built independently from the geometry.

### Problem 4. Area Between Curves
Find the area of the region bounded by the graphs
$$
y=x
$$
and
$$
y=x^2.
$$

First find the intersection points and justify which function is greater on the relevant interval.

> **Why this problem:** it teaches that before integrating, one must first determine the geometry of the region and the correct order of the functions.

### Problem 5. Distance from Velocity
The velocity of a car during the first five seconds is described by the function
$$
v(t)=4t+2\quad [\mathrm{m/s}].
$$

Compute the distance traveled and explain why the integral of velocity gives the change in position.

Then answer what would have to be changed in the reasoning if the velocity also took negative values.

> **Why this problem:** it connects the integral with accumulation and distinguishes displacement from the actual distance traveled.

### Problem 6. Average Value of a Function
Compute the average value of the function
$$
f(x)=x^2
$$
on the interval $[0,3]$.

Find a point $c\in[0,3]$ for which $f(c)$ is equal to this average value, and interpret the result geometrically.

> **Why this problem:** it gives the integral the interpretation of an average value and connects the numerical result with a level of the function on the graph.

### Problem 7. Exponential Growth
Assume the model
$$
N(t)=N_0e^{kt},\qquad k>0.
$$

1. Verify by differentiation that the model satisfies the relation $N'(t)=kN(t)$.
2. Find the population doubling time.
3. Explain why the doubling time does not depend on $N_0$.

> **Why this problem:** it shows the connection between the exponential function and a growth rate proportional to the current value, without introducing a separate technique for solving differential equations.

### Problem 8. Number of Requests Handled by a Server
The rate at which requests arrive at a server during the first 5 minutes is described by the function
$$
r(t)=100+20t\quad [\text{requests/min}],\qquad 0\le t\le5.
$$

1. Compute the total number of requests that arrived during this time.
2. Compute the average rate of incoming requests over this interval.
3. Compare the average rate with the values $r(0)$ and $r(5)$.

> **Why this problem:** it shows the integral as summation of a varying rate in an example directly related to computer science.

## More Difficult and Cross-Sectional Problems

### Problem 9. Minimizing the Material Used for a Can
A closed cylinder has fixed volume $V$.

1. Write the volume constraint.
2. Eliminate one of the variables.
3. Express the surface area as a function of the radius $r$.
4. Find the relation between the height $h$ and the radius $r$ for which the material usage is minimal.

Interpret the obtained relation geometrically.

> **Why this problem:** it requires independent reduction of a problem with two variables to one objective function and control of the geometric constraint.

### Problem 10. A Cable Through Water and Land
Point $A$ lies on one bank of a river of width $100$ m, and point $B$ lies on the other bank, $500$ m along the bank from the point directly opposite $A$.

The cost per meter of cable underwater is twice the cost per meter of cable on land.

Build a cost function depending on the point where the cable comes out of the water, determine the domain, and find the solution that minimizes the cost.

> **Why this problem:** it checks whether the student can independently translate a spatial description and two different costs into a single function to be optimized.

### Problem 11. Volume of a Solid of Revolution
The region under the graph
$$
y=\sqrt{x},\qquad x\in[0,4],
$$
is rotated about the $x$-axis.

1. Construct the integral describing the volume using the disk method.
2. Compute the volume.
3. Explain where the factor $\pi y^2$ in the integral comes from.

> **Why this problem:** it teaches how to construct an integral from the geometry of cross-sections instead of applying a volume formula without understanding its origin.

### Problem 12. Complete Model and Computer Verification
A museum wants to create a rectangular exhibition room next to an existing straight wall. The side along the wall does not need to be built. The remaining three sides are to be constructed to two different standards: the two sides perpendicular to the wall cost $300\ \mathrm{PLN/m}$ each, while the side parallel to the wall costs $500\ \mathrm{PLN/m}$. The budget is $30\,000\ \mathrm{PLN}$.

Build a model that maximizes the area of the room and prepare a complete analysis containing:

- definition of variables and units,
- mathematical model,
- domain resulting from the problem statement,
- computation of the derivative,
- determination and verification of the optimum,
- interpretation of the result,
- graph of the objective function,
- numerical verification of several values near the optimum found.

Finally, indicate which part of the solution required modeling the problem and which part was only the execution of the calculation. Produce the graph and computer calculations only after completing the mathematical solution, and treat them as verification.

> **Why this problem:** it checks full transfer to a new problem with unequal side costs and integrates the process from model construction to independent verification.
