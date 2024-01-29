---
title: "Polynomial functions"
weight: 5
---

# Polynomial Functions

So far we have understood about linear functions and quadratic functions. Now we shall generalize
these ideas. We call an expression of the form anx
n + an−1x
n−1 + · · · + a0 is called a polynomial
in the variable x, where ai ∈ R, i = 0, 1, 2, · · · , n. Here n is a non-negative integer. When an 6= 0,
we say that the polynomial has degree n. The numbers a0, a1, . . . , an ∈ R are called the coefficients
of the polynomial. The number a0 is called the constant term and an is called the leading coefficient
(when it is non-zero). It is clear that:
(i) 100x
7 − πx5 + 20√
2x
2 + 7x + 1.22 is a polynomial of degree 7.
(ii) (17x − 3)(x + 3)(2x −
√
π)(x + 2.3) is a polynomial of degree 4.
(iii) (x
2 + x + 1)(x
3 + 2x + 2)(x
5 − 5x +
√ 3) is a polynomial of degree 10.
One may substitute specific values for x, say x = c and obtain anc
n + an−1c
n−1 + · · · + a1c + a0.
A function of the form P(x) = anx
n + an−1x
n−1 + · · · + a0 is called a polynomial function which is
defined from R to R. We shall treat polynomial and polynomial function as one and the same.
A polynomial with degree 1 is called a linear polynomial. A polynomial with degree 2 is called
a quadratic polynomial. A cubic polynomial is one that has degree three. Likewise, degree 4 and
degree 5 polynomials are called quartic and quintic polynomials respectively. Note that any constant
a 6= 0 is a polynomial of degree zero!
Two polynomials f(x) = anx
n + an−1x
n−1 + · · · + a0, an 6= 0 and g(x) = bmx
m + bm−1x
m−1 +
· · · + b0, bm 6= 0 are equal if and only if f(x) = g(x) for all x ∈ R. It can be proved that f(x) = g(x)
if and only if n = m and ak = bk, k = 0, 1, 2, · · · n. Given two polynomials, one can form their
sum and product. For example if P(x) = 2x
3 + 7x
2 − 5 and Q(x) = x
4 − 2x
3 + x
2 + x + 1, then
P(x) + Q(x) = x
4 + 8x
2 + x − 4 (by adding the corresponding coefficients of the like powers of x)
and P(x)Q(x) = 2x
7 + 3x
6 − 12x
5 + 4x
4 + 19x
3 + 2x
2 − 5x − 5 by multiplying each term of P(x)
by every term of Q(x). It is easy to see that the degree of P(x)Q(x) is the sum of the degrees of P(x)
and Q(x), whereas the degree of P(x) + Q(x) is at most the maximum of degrees of P(x) and Q(x).
Here is an example of the graph of a cubic polynomial function.
–2–3–4–5 –1
–2
2
4
6
8
10
–4
–6
–8
–10
0 1 2 3 4 5 x
y
Figure 2.6
Suppose that f(x) and g(x) are polynomials where g(x) is not zero. The quotient f(x)
g(x)
is called a
rational function, which is defined for all x ∈ R such that g(x) 6= 0. In general, a rational function
need not be a polynomial.
64
www.tntextbooks.in
2.6 Polynomial Functions
2.6.1 Division Algorithm
Given two polynomials f(x) and g(x), where g(x) is not the zero polynomial, there exist two
polynomials q(x) and r(x) such that f(x) = q(x)g(x)+r(x) where degree of r(x) < degree of g(x).
Here, q(x) is called the quotient polynomial, and r(x) is called the remainder polynomial. If r(x) is
the zero polynomial, then q(x), g(x) are factors of f(x) and f(x) = q(x)g(x).
These terminologies are similar to terminologies used in division done with integers.
If g(x) = x − a, then the remainder r(x) should have degree zero and hence r(x) is a constant. To
determine the constant, write f(x) = (x − a)q(x) + c. Substituting x = a we get c = f(a).
Remainder Theorem
If a polynomial f(x) is divided by x−a, then the remainder is f(a). Thus the remainder c = f(a) = 0
if and only if x − a is a factor for f(x).
Definition 2.1
A real number a is said to be a zero of the polynomial f(x) if f(a) = 0. If x = a is a zero of
f(x), then x − a is a factor for f(x).
In general, if we can express f(x) as f(x) = (x − a)
k
.g(x) where g(a) 6= 0, then the value of k,
which depends on a, cannot exceed the degree of f(x). The value k is called the multiplicity of the
zero a.
(i) A polynomial function of degree n can have at most n distinct real zeros. It is
also possible that a polynomial function like P(x) = x
2 + 1 has no real zeros at
all.
(ii) Suppose that P(x) is a polynomial function having rational coefficients. If a +
b
√p where a, b ∈ Q, p a prime, is a zero of P(x), then its conjugate a − b
√p is
also a zero.
Two important problems relating to polynomials are
(i) Finding zeros of a given polynomial function; and hence factoring the polynomial into linear
factors and
(ii) Constructing polynomials with the given zeros and/or satisfying some additional conditions.
To address the problem of finding zeros of a polynomial function, some well known algebraic
identities are useful. What is an identity?
An equation is said to be an identity if that equation remains valid for all values in its domain. An
equation is called conditional equation if it is true only for some (not all) of values in its domain. Let
us recall the following identities.
2.6.2 Important Identities
For all x, a, b ∈ R we have

1. (x + a)
   3 = (x + a)
   2
   (x + a) = x
   3 + 3x
   2a + 3xa2 + a
   3 = x
   3 + 3xa(x + a) + a
   3
2. (x − b)
   3 = x
   3 − 3x
   2
   b + 3xb2 − b
   3 = x
   3 − 3xb(x − b) − b
   3
   (taking a = −b in (1))
3. x
   3 + a
   3 = (x + a)(x
   2 − xa + a
   2
   )
4. x
   3 − b
   3 = (x − b)(x
   2 + xb + b
   2
   ) taking a = −b in (3)
5. x
   n − a
   n = (x − a)(x
   n−1 + x
   n−2a + · · · + x
   n−k−1a
   k + · · · + a
   n−1
   ), n ∈ N
6. x
   n + b
   n = (x + b)(x
   n−1 − x
   n−2
   b + · · · + x
   n−k−1
   (−b)
   k + · · · + (−b)
   n−1
   ), n ∈ N
   65
   Basic Algebra
   Exercise - 2.6
7. Find the zeros of the polynomial function f(x) = 4x
   2 − 25.
8. If x = −2 is one root of x
   3 − x
   2 − 17x = 22, then find the other roots of equation.
9. Find the real roots of x
   4 = 16.
10. Solve (2x + 1)2 − (3x + 2)2 = 0.
    Method of Undetermined Coefficients
    Now let us focus on constructing polynomials with the given information using the method of
    undetermined coefficients. That is, we shall determine coefficients of the required polynomial using
    the given conditions. The main idea here is that two polynomials are equal if and only if the
    coefficients of same powers of the variables in the two polynomials are equal.
    Example 2.16 Find a quadratic polynomial f(x) such that, f(0) = 1, f(−2) = 0 and f(1) = 0.
    Solution:
    Let f(x) = ax2 + bx + c be the polynomial satisfying the given conditions.
    f(0) = a(0)2+b(0)+c = 1, implies that c = 1. Now the other two conditions f(−2) = 0, f(1) = 0
    give 4a − 2b + c = 0 and a + b + c = 0.
    Using c = 1, we get 4a−2b = −1 and a+b = −1. Solving these two equations we get a = b = −
    1
    2
    and thus, we have f(x) = −
    1
    2
    x
    2 −
    1
    2
    x + 1.
    The above problem can also be solved in another way. x = −2, x = 1 are zeros of
    f(x). Thus, f(x) = d(x + 2)(x − 1) for some constant d.
    Now using f(0) = 1 gives −2d = 1, hence d = −
    1
    2
    . So, f(x) = −
    1
    2
    (x+2)(x−1) =
    −
    1
    2
    x
    2 −
    1
    2
    x + 1.
    Example 2.17 Construct a cubic polynomial function with rational coefficients having zeros at
    x =
    2
    5
    , 1 + √
    3 such that f(0) = −8.
    Solution:
    Given that 2
    5
    and 1 + √
    3 are zeros of f(x). Thus, 1 −
    √
    3 is also a zero of f(x).
    Let f(x) = a(x −
    2
    5
    )[(x − (1 + √
    3))][x − (1 − √ 3)] = a(x −
    2
    5
    )[(x − 1)2 − 3].
    Using f(0) = −8, we have,
