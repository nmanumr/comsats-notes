# Lecture 01

```text
- Topic:    Introduction to Differential Equations
- Time:     Mon Feb 03 2020 21:30:00 GMT+0500 / PT30M
- Room:     C-5
```

## Recommended Book
[Differential Equations by DENNIS G. ZILL](http://instructor.sdu.edu.kz/~merey/DIFFERENTIAL%20EQUATIONS%20with%20Boundary-Value%20Problemsa%20Zill%20Cullen.pdf)[^1]

Alternatively notes might be available at Photocopier with Code `202`

## Course Outline
There are following chapter we will study through out the course from the above mentioned book:

* Chapter 02 - First order Differential Equations (Ex 2.2, 2.3, 2.4, 2.5)
* Chapter 03 - Modeling with First Differential Equations (Ex 3.2)
* Chapter 04 - Higher Order Differential Equations with constant coefficients (Ex 4.3, 4.4, 4.7)
* Chapter 06 - Higher Order Differential Equations with variable coefficients (Ex 6.1, 6.3)
* Chapter 08 - System of Linear Differential Equations (Ex 8.1, 8.6)
* Chapter 12 - Partial Differential Equations (Ex 12.3, 12.4)

## Intro to Differential Equations
Differential Equations are the equation involving derivatives.
For example, following is the algebraic equation of family of parabolas:

$$ y = x^2 + c $$

We can take can derivative of the above equation wrt $dx$ and write it as:

$$ \frac{dy}{dx} = 2x $$

This equation is called a differential equation and this also gives the same
family of parabolas.

## Types of Differential Equations
There are two type of differential equations:

1. Ordinary Differential Equation (ODEs): which involves ordinary derivatives like: $$ \frac{dy}{dx} = 2x $$
2. Partial Differential Equation (PDEs): which involves partial derivatives like: $$ \frac{\partial u}{\partial x} + \frac{\partial u}{\partial y} = 5 $$

!!! tip
    We normally use partial derivatives when a function have less then 1 independent variables.

## Solution of Differential Equations
For equation ($x^2+3x+2=0$) the solution are the values of $x$ that satisfies the equation (ie $x=-1$, $x=-2$).

Similarly solution of differential equation (ie $\frac{dy}{dx}=2x$) is the the value of dependent variable without
derivatives ($y$) which satisfies the equation. Theses solutions can be found by taking the integral on both side.

* 1st order differential equations required single integral for solution.
* 2nd order differential equations required double integral for solution.
* and so on...


But there are some optimal techniques that can be used to solve the higher
order differential equations.

## Solution types of Differential Equations
* Particular Solution ($y=x^2+2$): solution with fixed constant value.
* General Solution ($y=x^2+c$): solution with arbitrary constant value.

## Separation of Variable Method
* Works for 1st order differential equations. For example: $$ \frac{dy}{dx}=x ^2y ^2 $$ $$ \frac{dy}{dx}=\frac{x^2+1}{y+x} $$ $$ \frac{dy}{dx}=\frac{x+2y+1}{x^2+y} $$
* Only works if variables can be separated from the differential equation. For example:
    * Works for: $$ \frac{dy}{dx}=x ^2y ^2 $$
    * Not works for: $$ \frac{dy}{dx}=\frac{x^2+1}{y+x} $$
* So in general any equation of form <span class="ld">$$ \frac{dy}{dx}=\frac{f(x)}{g(y)} $$</span> can be solve be solved using this method.

### Solution Steps
* Separate the variables of the equation. like $$ \frac{dy}{dx}=x ^2y ^2 \implies \frac{dy}{y^2}=x ^2dx $$
* Apply integral on both side and solve the equation $$ \displaystyle\int\frac{dy}{y^2}=\displaystyle\int x ^2dx $$

## Exercise Solutions
* Questions Solved in class: 1, 6, 14, 34

[Exercise 2.2 on Slader](https://www.slader.com/textbook/9781111827069-differential-equations-with-boundary-value-problems-eighth-edition/51/)

[^1]: The book link wasn't provided the teacher.
