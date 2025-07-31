
## Feasible Region for a Linear Programming Problem

This example demonstrates how to visualize the feasible region for a simple linear programming problem with two variables, x and y, subject to two inequality constraints and non-negativity constraints (x >= 0, y >= 0).

The problem is defined by the following constraints:
1. $3x + 5y \leq 50$
2. $2x + 4y \leq 80$
3. $x \geq 0$
4. $y \geq 0$

The feasible region is the set of all points (x, y) that satisfy all of these constraints simultaneously.

## Defining and Plotting Constraints

We need to express the inequality constraints in terms of y to plot them.

1. Constraint 1: $3x + 5y \leq 50$
   Solving for y: $5y \leq 50 - 3x \implies y \leq (50 - 3x)/5$

2. Constraint 2: $2x + 4y \leq 80$
   Solving for y: $4y \leq 80 - 2x \implies y \leq (80 - 2x)/4 \implies y \leq (40 - x)/2$

Now, we can define the corresponding y values for each constraint based on the x values.

## Filling the Feasible Region

The feasible region is bounded by the constraint lines and the non-negativity constraints ($x \geq 0$ and $y \geq 0$). To shade this region, we find the minimum of the y values from the two constraints and ensure that the shaded area is above y = 0.

## Plot Settings and Feasible Corner Points

We set the limits for the x and y axes, add labels, a title, a legend, and a grid for better readability.

The feasible region's corner points are important as the optimal solution for a linear programming problem lies at one of these points. We mark some of these points on the plot. The corner points are the intersections of the constraint lines and the axes within the feasible region.
