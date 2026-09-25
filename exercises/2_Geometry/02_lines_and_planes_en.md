# Lines and Planes

## Goal of the Set

After completing this set, the student should be able to describe lines and planes using points, direction vectors, and normal vectors; move between the most important forms of equations; analyze the relative position of geometric objects; and compute intersections, angles, distances, and projections.

The set deliberately combines material on lines, planes, and line–plane relationships. The goal is not to master separate catalogs of formulas, but to recognize the common vector geometry behind them.

## Basic Exercises

### Exercise 1. Line Through Two Points
Find the equation of the line through $A=(1,2)$ and $B=(4,-1)$ in parametric and general form. Identify a direction vector and an example of a normal vector. Check that both points satisfy the equation you obtain.

> **Why this exercise:** teaches how to move between equivalent descriptions of a line and connect them with the appropriate vectors.

### Exercise 2. A Line in Space
Given
$$L:(x,y,z)=(2,-1,3)+t(1,2,-2).$$
State a point on the line and its direction vector, check whether $P=(4,3,-1)$ lies on $L$, and find the point corresponding to $t=-1$.

> **Why this exercise:** reinforces the interpretation of parametric form as “point + direction.”

### Exercise 3. Plane Through a Point with a Given Normal Vector
Find the equation of the plane through $P=(1,-2,3)$ and perpendicular to $n=(2,1,-1)$. Check the result by substituting the point $P$ and explain the role of the normal vector.

> **Why this exercise:** shows the basic construction of a plane from a point and a normal vector.

### Exercise 4. Plane Through Three Points
Find the equation of the plane through
$$A=(1,0,0),\quad B=(0,1,0),\quad C=(0,0,1).$$
First construct two vectors lying in the plane, and then use the cross product. Check the resulting equation on all three points.

> **Why this exercise:** connects earlier vector tools with constructing the equation of a plane.

### Exercise 5. Relative Position of Two Lines
Analyze the position of
$$L_1:(x,y,z)=(1,1,0)+t(1,2,1),$$
$$L_2:(x,y,z)=(2,0,1)+s(0,1,-1).$$
If they intersect, give the intersection point. If not, determine whether they are parallel or skew. Justify the classification.

> **Why this exercise:** teaches how to distinguish qualitatively different relationships between lines in space.

### Exercise 6. Angle Between Planes
Given
$$\Pi_1:x+y+z=1,\qquad \Pi_2:x-y=2.$$
First use the normal vectors to decide whether the planes are parallel. If not, compute the angle between them and explain why the normal vectors alone are enough for this calculation.

> **Why this exercise:** focuses attention on one mechanism—using normals to analyze position and angle—without also introducing the construction of the intersection line.

### Exercise 7. A Line Relative to a Plane
For
$$L:(x,y,z)=(1,1,0)+t(1,-1,0),\qquad \Pi:x+y+z=2,$$
determine whether the line intersects the plane at one point, is parallel to it, or lies in it. Explain the role of the dot product of the direction vector and the normal vector.

> **Why this exercise:** builds a universal test for the relative position of a line and a plane.

### Exercise 8. Intersection Point of a Line and a Plane
Find the intersection point of
$$(x,y,z)=(1,0,2)+t(1,2,-1)$$
with the plane $x+y+z=4$. Check the result by substituting it into both descriptions.

> **Why this exercise:** practices the most important computational case of the line–plane relationship.

### Exercise 9. Distances
Compute:
1. the distance from $P=(2,3)$ to the line $3x+4y-10=0$,
2. the distance from $Q=(2,-1,3)$ to the plane $2x-2y+z-4=0$.

Compare the two formulas and explain their common connection with the normal direction.

> **Why this exercise:** organizes two similar formulas through one geometric idea.

### Exercise 10. Projection of a Point onto a Plane
Find the orthogonal projection of $P=(2,1,3)$ onto the plane $x+y+z=3$, and then find the reflection of $P$ across this plane. Check that the midpoint of the segment joining the point and its reflection lies on the plane.

> **Why this exercise:** combines the normal, intersection, and distance into the construction of a projection and reflection.

## More Challenging Exercises

### Exercise 11. Plane Containing a Line and a Point
Find the equation of the plane containing
$$(x,y,z)=(1,0,2)+t(1,1,-1)$$
and the point $P=(0,2,1)$. Check that both the entire line and the point lie in the plane you obtain.

> **Why this exercise:** requires independently constructing two linearly independent directions in the plane.

### Exercise 12. Intersection Line of Two Planes
Find a parametric equation of the line that is the intersection of
$$x+y+z=3,\qquad x-y+z=1.$$
Find its direction vector in two ways: from the system of equations and from the cross product of the normal vectors. Compare the results.

> **Why this exercise:** shows the equivalence of the algebraic and geometric approaches to constructing an intersection line.

### Exercise 13. Closest Point on a Plane
Find the point on the plane $x+2y+2z=4$ closest to $P=(3,0,0)$. Give the distance and check that the segment joining the two points is perpendicular to the plane.

> **Why this exercise:** combines projection, distance, and the normal direction in one problem.

### Exercise 14. Contrast: Intersection and Parallelism
From the point $P=(0,0,1)$, two lines are drawn with direction vectors
$$v_1=(2,1,-1),\qquad v_2=(2,1,0).$$
For each line, analyze its position relative to the plane $z=0$.

For the line that intersects the plane, find the intersection point. For the other line, explain how you can recognize parallelism without solving an equation.

> **Why this exercise:** compares two very similar data sets that lead to different outcomes and forces recognition of the geometric condition before calculation.

### Exercise 15. Complete Classification of a Line Relative to a Plane
Let
$$L:p+tv,\qquad \Pi:n\cdot x=d.$$
State the conditions distinguishing the three cases: one intersection point, parallel with no common points, and the line contained in the plane. Then illustrate each case with your own simple numerical example.

> **Why this exercise:** requires formulating a general mathematical criterion instead of carrying out one isolated calculation.
