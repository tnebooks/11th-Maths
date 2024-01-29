---
title: "Rational functions"
weight: 6
---

# Rational Functions

A rational expression of x is defined as the ratio of two polynomials in x, say P(x) and Q(x) where
Q(x) 6= 0. Examples of rational expressions are 2x + 1
x
2 + x + 1
,
x
4 + 1
x
2 + 1
and x
2 + x
x
2 − 5x + 6
.
If the degree of the numerator P(x) is equal to or larger than that of the denominator Q(x), then
we can write P(x) = f(x)Q(x)+r(x) where r(x) = 0 or the degree of r(x) is less than that of Q(x).
So
P(x)
Q(x)
= f(x) + r(x)
Q(x)
.
2.7.1 Rational Inequalities
Example 2.24 Solve x + 1
x + 3
< 3.
Solution:
Subtracting 3 from both sides we get x + 1
x + 3
− 3 < 0.
68
www.tntextbooks.in
2.7 Rational Functions
x + 1 − 3(x + 3)
x + 3
< 0
−2x − 8
x + 3
< 0
x + 4
x + 3

> 0
> Thus, x + 4 and x + 3 are both positive or both negative.
> So let us find out the signs of x + 3 and x + 4 as follows
> x x + 3 x + 4
> x + 4
> x + 3
> x < −4 − − +
> −4 < x < −3 − + −
> x > −3 + + +
> x = −4 − 0 0
> So the solution set is given by (−∞, −4) ∪ (−3, ∞).
> The above type of rational inequality problem can also be solved by plotting the signs
> of various factors on the intervals of the number line.
> Exercise - 2.8

1. Find all values of x for which x
   3
   (x − 1)
   (x − 2) > 0.
2. Find all values of x that satisfies the inequality 2x − 3
   (x − 2)(x − 4) < 0.
3. Solve x
   2 − 4
   x
   2 − 2x − 15
   ≤ 0.
   2.7.2 Partial Fractions
   A rational expression f(x)
   g(x)
   is called a proper fraction if the degree of f(x) is less than degree of g(x),
   where g(x) can be factored into linear factors and quadratic factors without real zeros. Now f(x)
   g(x)
   can
   be expressed in simpler terms, namely, as a sum of expressions of the form
   (i) A1
   (x − a)

- A2
  (x − a)
  2
- · · · +
  Ak
  (x − a)
  k
  if x − a divides g(x) and
  (ii) (B1x + C1)
  (x
  2 + ax + b)
- (B2x + C2)
  (x
  2 + ax + b)
  2
- · · · +
  (Bkx + Ck)
  (x
  2 + ax + b)
  k
  if x
  2 + ax + b has no real zeros and
  (x
  2 + ax + b) divides g(x).
  The resulting expression of f(x)
  g(x)
  is called the partial fraction decomposition. Such a decomposition
  is unique for a given rational function.
  This method is useful in doing Integral calculus. So let us discuss some examples.
  69
  www.tntextbooks.in
  Basic Algebra
  Example 2.25 Resolve into partial fractions: x
  (x + 3)(x − 4).
  Solution:
  Let
  x
  (x + 3)(x − 4)=
  A
  x + 3
- B
  x − 4
  where A and B are constants.
  Then, x
  (x + 3)(x − 4) =
  A(x − 4) + B(x + 3)
  (x + 3)(x − 4) , which gives x = A(x − 4) + B(x + 3).
  When x = 4, we have B =
  4
  7
  .
  When x = −3, we have A =
  3
  7
  Hence,
  x
  (x + 3)(x − 4)=
  3
  7(x + 3) +
  4
  7(x − 4).
  The above procedure can be carried out if the denominator has all its zeros in R which
  are all distinct.
  Example 2.26 Resolve into partial fractions: 2x
  (x
  2 + 1)(x − 1).
  Solution:
  In this case, note that the denominator has a factor x
  2 + 1 which does not have real zeros.
  Let
  2x
  (x
  2 + 1)(x − 1) =
  A
  (x − 1) +
  Bx + C
  x
  2 + 1
  where A, B, C are constants.
  We have, 2x = A(x
  2 + 1) + (Bx + C)(x − 1).
  When x = 1, we get A = 1.
  When x = 0, we have A − C = 0 and hence A = C = 1.
  When x = −1, we have 2A − 2(C − B) = −2, which gives B = −1.
  Thus, 2x
  (x
  2 + 1)(x − 1) =
  1
  (x − 1) +
  1 − x
  x
  2 + 1
  We now illustrate the situation when denominator has a real zeros with multiplicity more than one.
  Example 2.27 Resolve into partial fractions: x + 1
  x
  2(x − 1).
  Solution:
  Let
  x + 1
  x
  2(x − 1) =
  A
  x
- B
  x
  2
- C
  x − 1
  .
  Then, x + 1 = Ax(x − 1) + B(x − 1) + Cx2
  .
  When x = 0, we have B = −1 and when x = 1, we get C = 2.
  When x = −1, we have 2A − 2B + C = 0 which gives A = −2.
  Thus, x + 1
  x
  2(x − 1) =
  −2
  x
  −
  1
  x
  2
- 2
  x − 1
  .
  70
  www.tntextbooks.in
  2.7 Rational Functions
  Exercise - 2.9
  Resolve the following rational expressions into partial fractions.

1.  1
    x
    2 − a
    2
2.  3x + 1
    (x − 2)(x + 1) 3.
    x
    (x
    2 + 1)(x − 1)(x + 2) 4.
    x
    (x − 1)3
3.  1
    x
    4 − 1
4.  (x − 1)2
    x
    3 + x
5.  x
    2 + x + 1
    x
    2 − 5x + 6
6.  x
    3 + 2x + 1
    x
    2 + 5x + 6
7.  x + 12
    (x + 1)2(x − 2) 10.
    6x
    2 − x + 1
    x
    3 + x
    2 + x + 1
8.  2x
    2 + 5x − 11
    x
    2 + 2x − 3
9.  7 + x
    (1 + x)(1 + x

2)  2.7.3 Graphical Representation of Linear Inequalities
    A straight line ax + by = c divides the Cartesian plane into two parts. Each part is an half plane. A
    vertical line x = c will divide the plane in left and right half planes and a horizontal line y = k will
    divide the plane into upper and lower half planes.
    A point in the cartesian plane which is not on the line ax + by = c will lie in exactly one of
    the two half planes determined by the line and satisfies one of the inequalities ax + by < c or
    ax + by > c.
    To identify the half plane represented by ax + by < c, choose a point P in any one of the half
    planes and substitute the coordinates of P in the inequality.
    If the inequality is satisfied, then the required half plane is the one that contains P; otherwise the
    required half plane is the one that does not contain P. When c 6= 0, it is most convenient to take P to
    be the origin.
    Example 2.28 Shade the region given by the inequality x ≥ 2.
    Solution:
    First we consider equation x = 2.
    It is a line parallel to y axis at a
    distance of 2 units from it. This
    line divides the cartesian plane into
    two parts. Substituting (0, 0) in the
    inequality we get 0 ≥ 2 which is
    false. Hence the region which does
    not contain the origin is represented
    by the inequality x ≥ 2. The shaded
    region is the required solution set of
    the given inequality. Since x ≥ 2,
    the points on the line x = 2 are also
    solutions.
    x
    y
    –1 0
    –1
    –2
    –3
    1
    2
    3
    4
    1 2 3 4 5
    x ³ 2
    71

    Example 2.29 Shade the region given by the linear inequality x + 2y > 3.
    Proof. The line x + 2y = 3 divides the
    cartesian plane into two half planes. To
    find the half plane represented by x +
    2y > 3 substitute a point in one of the
    half planes in the inequality and check
    whether it is satisfied. Let us substitute
    (0, 0) in the inequality. We get 0 > 3
    which is false. Hence, the region given
    by x + 2y > 3 is the half plane which
    does not contain the origin.
    x
    y
    –1 0
    –1
    –2
    –3
    1
    2
    3
    4
    1 2 3 4 5
    x + 2y ³ 3
    Example 2.30 Solve the linear inequalities and exhibit the solution set graphically:
    x + y ≥ 3, 2x − y ≤ 5, −x + 2y ≤ 3.
    Solution:
    Observe that a straight line can be drawn if we identify any two points on it. For example, (3, 0)
    and (0, 3) can be easily identified as two points on the straight line x + y = 3.
    Draw the three straight lines x + y = 3, 2x − y = 5 and −x + 2y = 3.
    Now (0, 0) does not satisfy x + y ≥ 3. Thus, the half plane bounded by x + y = 3, not containing
    the origin, is the solution set of x + y ≥ 3.
    Similarly, the half-plane bounded by
    2x − y ≤ 5 containing the origin represents the solution set of the 2x − y ≤ 5.
    The region represented by
    −x + 2y ≤ 3 is the half space bounded
    by the straight line −x + 2y = 3 that
    contains the origin.
    The region common to the above
    three half planes represents the solution
    set of the given linear inequalities. x
    y
    –1 0
    –1
    –2
    –3
    1
    2
    3
    4
    1 2 3 4 5
    2x – y = 5
    x + y = 3
    –x + 2y = 3
    72

    2.8 Exponents and Radicals
    Exercise - 2.10
    Determine the region in the plane determined by the inequalities:
    (1) x ≤ 3y, x ≥ y.
    (2) y ≥ 2x, −2x + 3y ≤ 6.
    (3) 3x + 5y ≥ 45, x ≥ 0, y ≥ 0.
    (4) 2x + 3y ≤ 35, y ≥ 2, x ≥ 5.
    (5) 2x + 3y ≤ 6, x + 4y ≤ 4, x ≥ 0, y ≥ 0.
    (6) x − 2y ≥ 0, 2x − y ≤ −2, x ≥ 0, y ≥ 0.
    (7) 2x + y ≥ 8, x + 2y ≥ 8, x + y ≤ 6.
