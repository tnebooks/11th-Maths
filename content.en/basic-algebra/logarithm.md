---
title: "Logarithm"
weight: 8
---

# Logarithm

We have seen that, with a base 0 < a 6= 1, the exponential function f(x) = a
x
is defined on R having
range (0, ∞). We also observed that f(x) is a bijection, hence it has an inverse. We call this inverse
function as logarithmic function and is denoted by loga
(.). Let us discuss this function further. Note
that if f(x) takes x to y = a
x
, then loga
(.) takes y to x. That is, for 0 < a 6= 1, we have
y = a
x
is equivalent to loga y = x.
For example, since 3
4 = 81 we have log3
(81) = 4. In other words, with fixed a, given a real
number y, logarithm finds the exponent x satisfying a
x = y. This is useful in addressing practical
problems like, “how long will it take for certain investment to reach a fixed amount?” Logarithm is
also very useful in multiplying very small or big numbers.
(i) Note that exponential function a
x
is defined for all x ∈ R and a
x > 0 and so
loga
(·) defined only for positive real numbers.
(ii) Also, a
0 = 1 for any base a and hence loga
(1) = 0 for any base a.
77
www.tntextbooks.in
Basic Algebra
2.9.1 Properties of Logarithm
(i) a
loga x = x for all x ∈ (0, ∞) and loga
(a
y
) = y for all y ∈ R.
(ii) For any x, y > 0, loga
(xy) = loga x + loga y. (Product Rule)
(iii) For any x, y > 0, loga

x
y

= loga x − loga y. (Quotient Rule)
(iv) For any x > 0 and r ∈ R, loga x
r = r loga x. (Power Rule)
(v) For any x > 0, with a and b as bases, logb x =
loga x
loga
b
. (Change of base formula.)
Proof. Since exponential function with base a and logarithm function with base a are inverse of each
other,
(i) follows by using the definitions.
(ii) For x, y > 0 let loga x = u, loga y = v, and loga
(xy) = w. Rewriting these in the exponential
form we obtain a
u = x, a
v = y, and, a
w = xy. So, a
w = xy = a
ua
v = a
u+v
; thus w = u + v.
Thus, we obtain loga
(xy) = loga x + loga y.
(iii) Let loga x = u, loga y = v, and loga
x
y
= w. Then a
u = x, a
v = y and a
w =
x
y
. Hence,
a
w =
x
y
=
a
u
a
v
= a
u−v
; which implies w = u − v.
Thus, we obtain loga

x
y

= loga x − loga y.
(iv) Let loga x = u. Then a
u = x and therefore, x
r = (a
u
)
r = a
ru. Thus, loga x
r = ru = r loga x.
(v) Let logb x = v. We have b
v = x. Taking logarithm with base a on both sides we get
loga
b
v = loga x.
On the other hand loga
b
v = v loga
b by the Power rule. Therefore, v loga
b = loga x.
Hence logb x =
loga x
loga
b
, b > 0. This completes the proof.
Remark:
(i) If a = 10, then the corresponding logarithmic function log10 x is called the common logarithm.
(ii) If a = e,(an irrational number, approximately equal to 2.718), then the corresponding
logarithmic function loge x is called the natural logarithm. It is denoted by ln x. These
above particular cases of logarithmic functions are used very much in other sciences and
engineering. Particularly, the natural logarithm occurs very naturally. When we write log x we
mean loge x.
(iii) If a = 2, then the corresponding logarithmic function log2 x called the binary logarithm, which
is used in computer science.
(iv) Observe that loga 35 = loga
(7 ∗ 5) = loga 7 + loga 5; loga
50
3
= loga 50 −
loga 3.
loga 22x = x loga 22; log5 50 =
log10 50
log10 5
.
(v) Observe the graph of the logarithmic and exponential functions.
78
www.tntextbooks.in
2.9 Logarithm
–1
–2
–1
1
2
3
4
5
6
7
8
–3
1 2 3 4 5 6 7 8
y = log2
x
y = 2x
x –2
y
Figure 2.9
Example 2.34 Find the logarithm of 1728 to the base 2
√ 3.
Solution:
Let log2
√
3
1728 = x.
Then we have (2√
3)x = 1728 = 26 3
3 = 26
(
√
3)6
.
Hence, (2√
3)x = (2√
3)6
.
Therefore x = 6. That is, log2
√
3
1728 = 6.
Example 2.35 If the logarithm of 324 to base a is 4, then find a.
Solution:
We are given loga 324 = 4, which gives
a
4 = 324 = 34
(
√
2)4
. Therefore a = 3√ 2.
Example 2.36 Prove log 75
16
− 2 log 5
9

- log 32
  243
  = log 2.
  Solution:
  Using the properties of logarithm, we have
  log 75
  16
  − 2 log 5
  9
- log 32
  243
  = log 75 − log 16 − 2 log 5 + 2 log 9 + log 32 − log 243. (By Quotient
  rule)
  = log 3 + log 25 − log 16 − log 25 + log 81 + log 16 + log 2 − log 81 − log 3
  = log 2.
  Example 2.37 If log2 x + log4 x + log16 x =
  7
  2
  , find the value of x.
  Solution:
  Note that x > 0.
  log2 x + log4 x + log16 x =
  7
  2
  becomes 1
  logx 2
- 1
  logx 4
- 1
  logx 16
  =
  7
  2
  . (change of base rule)
  Thus 1
  a
- 1
  2a
- 1
  4a
  =
  7
  2
  where a = logx 2. That is 7
  4a
  =
  7
  2
  .
  79
  www.tntextbooks.in
  Basic Algebra
  Thus, a =
  1
  2
  and so, logx 2 =
  1
  2
  which gives x
  1
  2 = 2.
  Thus, x = 22 = 4.
  Example 2.38 Solve x
  log3 x = 9.
  Solution:
  Let log3 x = y.
  Then x = 3y
  and so, 3
  y
  2
  = 9.
  Thus, y
  2 = 2, which implies y =
  √
  2, −
  √

2. Hence, x = 3
   √
   2
   , 3
   −
   √
3. Example 2.39 Compute log3 5 log25 27.
   Solution:
   log3 5 log25 27 = log3 5 log25 3
   3
   .
   = log3 5 × 3 log25 3 (by exponent rule)
   = 3 log25 5 = 3
   log5 25 =
   3
   2 log5 5 =
   3
   2
   .
   Example 2.40 Given that log10 2 = 0.30103, log10 3 = 0.47712 (approximately), find the number
   of digits in 2
   8
   .3
   12
   .
   Solution:
   Suppose that N = 283
   12 has n + 1 digits. Then N can be written as 10n × b where 1 ≤ b < 10.
   Taking logarithm to the base 10, we get
   log N = log(10n
   b) = n log 10 + log b = n + log b.
   On the other hand,
   log N = log 283
   12 = 8 log 2 + 12 log 3 = 8 × 0.30103 + 12 × 0.47712 = 8.13368.
   Thus, we get n + log b = 8.13368. Since 1 ≤ b < 10 the number of digits is 9.
   Exercise - 2.12
4. Let b > 0 and b 6= 1. Express y = b
   x
   in logarithmic form. Also state the domain and range of the
   logarithmic function.
5. Compute log9 27 − log27 9 .
6. Solve log8 x + log4 x + log2 x = 11.
7. Solve log4 2
   8x = 2
   log2 8
   .
8. If a
   2 + b
   2 = 7ab, show that log a + b
   3
   =
   1
   2
   (log a + log b).
9. Prove log a
   2
   bc + log b
   2
   ca

- log c
  2
  ab = 0.

7. Prove that log 2 + 16 log 16
   15

- 12 log 25
  24
- 7 log 81
  80
  = 1.

8. Prove loga
   2 a logb
   2 b logc
   2 c =
   1
   8
   .
9. Prove log a + log a
   2 + log a
   3 + · · · + log a
   n =
   n(n + 1)
   2
   log a.
   80
   www.tntextbooks.in
   Exercise
10. If log x
    y − z
    =
    log y
    z − x
    =
    log z
    x − y
    , then prove that xyz = 1.
11. Solve log2 x − 3 log 1
    2
    x = 6.
12. Solve log5−x
    (x
    2 − 6x + 65) = 2.
