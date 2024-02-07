---
title: "Exponents and radicals"
weight: 7
---

# Exponents and Radicals

First we shall consider exponents.
2.8.1 Exponents
Let n ∈ N, a ∈ R. Then a
n = a · a · · · a (n times). If m is a negative integer and the real number
a 6= 0, then a
m =
1
a
−m
.
Note that for any a 6= 0, we have a
a
= a
1−1 = a
0 = 1. It is also easy to see the following
properties.
Properties of Exponents
(i) For m, n ∈ Z and a 6= 0, we have a
ma
n = a
m+n
.
(ii) For m, n ∈ Z and a 6= 0, we have a
m
a
n
= a
m−n
.
2.8.2 Radicals
Question:
For a 6= 0 and r ∈ Q, is it possible to define a
r
?
First let us consider the case when r =
1
n
, n ∈ N. Suppose there is a real number y ∈ R such that
y = a
1
n . Then we must have y
n = a.
This problem is basically to finding inverse function of y = x
n
. In order to understand better let
us consider the graphs of the following functions:
(i) f(x) = x
2n
, n ∈ N (ii) g(x) = x
2n+1, n ∈ N
From these two figures it is clear that the function g : R → R given by g(x) = x
2n+1, n ∈ N is
one-to-one and onto and hence its inverse function from R onto R exists. But f : R → [0, ∞) given
by f(x) = x
2n
, n ∈ N is onto but not one-to-one. However, f is one-to-one and onto if we restrict
its domain to [0, ∞). This is helpful in understanding nth root of a real number. So we have two cases;
Case 1 When n is even.
In this case y
n = a is not meaningful when a < 0. So no such y exists when a < 0.
Assume that a > 0. If y is a solution to x
n = a, then −y is also solution to x
n = a.
Case 2 When n is odd.
In this case no such problem arises as in Case 1. For y ∈ R, there is a unique x ∈ R such that
y = x
n
.
Based on the above observation we define radicals as follow.
Definition 2.2
(i) For n ∈ N, n even, and b > 0, there is a unique a > 0 such that a
n = b.
(ii) For n ∈ N, n odd, b ∈ R, there is a unique a ∈ R such that a
n = b. In both cases a is
called the nth root of b or radical and is denoted by b
1/n or √n
b
(i) If n = 2, then nth root is called the square root; if n = 3, then it is called cube
root.
(ii) Observe that the equation x
2 = a
2
√ , has two solutions x = a, x = −a; but
a
2 = |a|.
(iii) Properties of exponents given above are still valid for radicals provided each of
the individual terms are defined.
(iv) Note that for n ∈ N and a 6= 0 we have
(a
n
)
1/n =

|a| if n is even ,
a if n is odd .
For example, p4
(−2)4 = 161/4 = 2, 3431/3 = 7 and (−1000) 1
3 = −10.
For any rational r =
m
n
, m ∈ Z, n ∈ N, with gcd(m, n) = 1 and for a > 0 we define a
r = a
m
n =
(a
1/n)
m.
For example, 493/2 = (491/2
)
3 = 73 = 343. But (−49)3/2 has no meaning in real number system
because there is no real number x such that x
2 = (−49)3
.
2.8.3 Exponential Function
Observe that for any a > 0 and x ∈ R, a
x
can be defined. If a = 1, we define 1
x = 1. So we shall
consider a
x
, x ∈ R for 0 < a 6= 1. Here a
x
is called exponential function with base a. Note that
a
x may not be defined if a < 0 and x =
1
m
for even m ∈ N. This is why we restrict to a > 0. Also,
a
x > 0 for all x ∈ R. It does also satisfy the following:
Properties of Exponential Function
For a, b > 0 and a 6= 1 6= b
(i) a
x+y = a
x a
y
for all x, y ∈ R
(ii) a
x
a
y
= a
x−y
for all x, y ∈ R,
74
www.tntextbooks.in
2.8 Exponents and Radicals
(iii) (a
x
)
y = a
xy for all x, y ∈ R,
(iv) (ab)
x = a
x
b
x
for all x ∈ R,
(v) a
x = 1 if and only if x = 0.

1. Let us consider f(x) = a
   x
   , x ∈ R where a = 2.
   Now f(x) = 2x
   , x ∈ R. Let us show that f is one-to-one and onto.
   Suppose f(u) = f(v) for some u, v ∈ R. Then, we have 2
   u = 2v
   , which implies that 2
   u
   2
   v
   = 1,
   ⇒ 2
   u−v = 1.
   So, u − v = 0 and hence u = v. Thus f is a one-to-one function.
   From the graph it is clear that values of f(x) = 2x
   increase as x values increase and the range
   of f is (0, ∞). So as 2
   0 = 1, we have 2
   x > 1 for all x > 0 and 2
   x < 1 for all x < 0. Observe that
   f : R → (0, ∞) is onto.
2. Let us consider a =
   1
   2
   . Let g(x) = 
   1
   2
   x
   =
   1
   2
   x
   , x ∈ R.
   From the graph it is clear that the values of g(x) = 
   1
   2
   x
   decrease as x values increase and
   g(R) = (0, ∞). Also, g(0) = 1 we have g(x) > 1 for all x < 0 and g(x) < 1 for all x > 0.
   Remark: Exactly same arguments as above would show that an exponential function f(x) = a
   x
   , for
   any base 0 < a 6= 1, is one-to-one and onto with domain R and codomain (0, ∞).
   A Special Exponential Function
   Among all exponential functions, f(x) = e
   x
   , x ∈ R is the most important one as it has applications in
   many areas like mathematics, science and economics. Then what is this e? The following illustration
   from compounding interest problem leads to the constant e.
   Illustration
   2.8.3.1 Compound Interest
   Recall that if P is the principal, r =
   interest rate
   100
   , n is the number of compounding periods in a year
   and t is the number of years, then A = P
   n 10 100 10000 100000 100000000
   An 2.593742460 2.704813829 2.718145927 2.718268237 2.718281815
   We notice that as n gets really large, An values seem to be getting closer to 2.718281815..... Actually
   An values approach a real number e, an irrational number. 2.718281815 is an approximation to e. So
   the compound interest formula becomes A = P ert, where r is the interest rate and P is the principal
   and t is the number of years. This is called Continuous Compounding.
   Example 2.31 (i) Simplify: (x
   1/2y
   −3
   )
   1/2
   ; where x, y ≥ 0.
   (ii) Simplify: √
   x
   2 − 10x + 25.
   Solution:
   (i) Since x, y ≥ 0, we have (x
   1/2y
   −3
   )
   1/2 = x
   1/4/y3/2
   .
   (ii) Observe that √
   x
   2 − 10x + 25 = p
   (x − 5)2 = |x − 5|
   (i) (x
   1/4
   )
   4 = x but (y
   4
   )
   1/4 = |y|.
   Observe that x
   1/4
   is defined only when x is positive. But y
   4
   is defined even
   when y < 0.
   Now (y
   4
   )
   1/4
   is a positive number whose fourth power equals y
   4
   . So it has to
   be |y|.
   (ii) (x
   8
   .y4
   )
   1/4 = x
   2
   |y|.
   (iii) Let u, v, b be rational numbers where b is positive.
   Let us suppose they are not squares of rational numbers.
   Then u + v
   √
   b, u − v
   √
   b are called conjugates.
   Observe that (u + v
   √
   b)(u − v
   √
   b) = u
   2 − bv2
   is now rational.
   Thus, if an expression such as u + v
   √
   b appears in the denominator we can
   multiply both the numerator and denominator by its conjugate, namely, u−v
   √
   b,
   to get a rational number in the denominator.
   (iv) Using (u
   √
   a − v
   √
   b)(u
   √
   a + v
   √
   b) = u
   2a − v
   2
   b, it is possible to simplify
   expressions when u
   √
   a + v
   √
   b occurs in the denominator.
   Example 2.32 Rationalize the denominator of
   √
   5
   (
   √
   6 + √

2)  .
    Solution:
    Multiplying both numerator and denominator by (
    √
    6 −
    √
    2),we get
    √
    5
    (
    √
    6 + √
3)  =
    √
    5(√
    6 −
    √
4)  (
    √
    6 + √
    2)(√
    6 −
    √
5)  =
    (
    √
    30 −
    √
6)  4
    .
    Example 2.33 Find the square root of 7 − 4
    √

3. Solution:
   Let p
   7 − 4
   √
   3 = a + b
   √
   3 where a, b are rationals.
   Squaring on both sides, we get 7 − 4
   √
   3 = a
   2 + 3b
   2 + 2ab√
4. So, a
   2 + 3b
   2 = 7 and 2ab = −4.
   Therefore a = −2/b.
   From a
   2 + 3b
   2 = 7, we get (−2/b)
   2 + 3b
   2 = 7, which gives 4/b2 + 3b
   2 = 7 or 3b
   4 −7b
   2 + 4 = 0.
   Solving for b
   2 we get b
   2 =
   (7±
   √
   49−48)
   6
   , which gives b
   2 = 1 or b
   2 =
   4
   3
   .
   Thus, b = ±1 or b = ± √
   2
   3
   .
   Since b is rational, we have b = ±1 and hence the corresponding values of a are ∓2.
   Since p
   7 − 4
   √
   3 > 0, we have p
   7 − 4
   √
   3 = 2 −
   √
5. It is not always possible to express square roots of u + v
   √
   b where u, v are rationals, in
   the form x + y
   √
   b with x, y rationals. For example, the square root of 1 + √
   2 is not of
   the form a + b
   √
   2 with a, b rationals.
   Exercise - 2.11
6. Simplify:
   (i) (125) 2
   3 , (ii) 16 −3
   4 , (iii) (−1000) −2
   3 , (iv) (3−6
   )
   1
   3 , (v)
   27 −2
   3
   27 −1
   3
   .
7. Evaluate 
8. If (x
   1/2 + x
   −1/2
   )
   2 = 9/2, then find the value of (x
   1/2 − x
   −1/2
   ) for x > 1.
9. Simplify and hence find the value of n: 3
   2n9
   23
   −n/3
   3n = 27.
10. Find the radius of the spherical tank whose volume is 32π/3 units.
11. Simplify by rationalising the denominator. 7 + √
    6
    3 −
    √
    2
    .
12. Simplify 1
    3 −
    √
    8
    −
    1
    √
    8 −
    √
    7

- 1
  √
  7 −
  √
  6
  −
  1
  √
  6 −
  √
  5
- 1
  √
  5 − 2
  .

8. If x =
   √
   2 + √
   3 find x
   2 + 1
   x
   2 − 2
   .
