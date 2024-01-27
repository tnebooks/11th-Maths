---
title: 'Infinite sequences and series'
weight: 6
---

# 5.6 Infinite Sequences and Series #
A finite sum of real numbers is well defined by the properties of real numbers, but in order to make sense of an infinite series, we need to consider the concept of convergence. Consider the infinite sum:
1/2 +1/4 +1/8 + · · · with each term positive. Can we assign a numerical value to the sum? While at first it may seem difficult or impossible. We can certainly do something similar where we have one quantity getting closer and closer to a fixed quantity.

Let us discuss an interesting problem. Let there be two plates A and B. Let a full cake be placed on the plate A and let B as empty. Let us cut the cake in A into exactly two equal parts and place one part on B leaving the other part in A. Let us cut the remaining part of the cake in A into exactly two equal parts and place one part on B leaving the other part in A. Let us again cut the remaining part of the cake in A into exactly two equal parts and place one part on B leaving the other part in A. If we go on doing this what will happen? What will be the amount of cake “finally” in A and in B? Let us list the stage by stage status:

Intuitively we feel that “finally” nothing will remain in plate A and the full cake will be in plate B. In other words, the cake available in A is 0 and the cake available in B is 1. That is, intuitively we feel that

1,
1
2
,
1
4
,
1
8
,
1
16
,
1
32
, . . .
“goes” to 0 and
1
2
,
1
2
+
1
4
,
1
2
+
1
4
+
1
8
,
1
2
+
1
4
+
1
8
+
1
16
, . . .
“goes” to 1 or equivalently
1
2
+
1
4
+
1
8
+
1
16
+ . . . is 1.
In this section let us learn the sense in which the words “finally” and “goes” are used and also let us
learn the addition of infinitely many numbers.
We intuitively feel that 1,
1
2
,
1
4
,
1
8
,
1
16 ,
1
32 , . . . “goes” to 0. Similarly we feel that the sequence 1,
1
10 ,
1
100 ,
1
1000 ,
1
10000 ,
1
100000 , . . . also “goes” to 0.
If (an) is a sequence and a is a number so that for any given small positive number, there is a stage after which the distance between an and a is smaller than that positive number, then we may say
that an goes to a as n goes to infinity. In technical terms we may say that an tends to a as n tends to infinity. In other words, in the limiting case an becomes a or the limit of an is a as n tends to ∞. We
also say that the sequence (an) converges to a. If (an) converges to a, then we write limn→∞ an = a.

At the same time we cannot say that the sequence
1, 0, 1, 0, 1, 0, 1, 0, 1, 0, . . .
goes to some number. In other words, this sequence do not converge to any limit. So a sequence may
not have a limit. But we can prove that a sequence cannot converge to more than one limit; that is, if
a sequence converges to a limit, then it is unique.
5.6.1 Fibonacci Sequence
The Fibonacci sequence is a sequence of numbers where a number other than first
two terms, is found by adding up the two numbers before it. Starting with 1, the
sequence goes 1, 1, 2, 3, 5, 8, 13, 21, 34, and so forth. Written as a rule, the
expression is xn = xn−1 + xn−2, n ≥ 3 with x1 = 1, x2 = 1
Named after Fibonacci, also known as Leonardo of Pisa or Leonardo Pisano,
Fibonacci numbers were first introduced in the book Liber abaci in 1202. The son
of a Pisan merchant, Fibonacci traveled widely and traded extensively. Mathematics
was incredibly important to those in the trading industry, and his passion for
numbers was cultivated in his youth.
Knowledge of numbers is said to have first originated in the Hindu-Arabic arithmetic system,
which Fibonacci studied while growing up in North Africa. Prior to the publication of Liber abaci, the
Latin-speaking world had yet to be introduced to the decimal number system. He wrote many books
about geometry, commercial arithmetic and irrational numbers. He also helped in the development of
the concept of zero.
n = 1 2 3 4 5 6 7 8 9 10 11 12 13 14 · · ·
xn = 1 1 2 3 5 8 13 21 34 55 89 144 233 377 · · ·
For example, The 8
th term is sum of 6
th term and 7
th term. Thus, x8 = 8 + 13 = 21.

**Infinite Series**

If (an) is an infinite sequence of numbers, then the formal expression a_1+a_2+· · · is called an infinite
series and is denoted as

{{<katex>}}\sum_{i=1}^∞ a_k{{</katex>}}

In the beginning of the section we have seen the infinite series

{{<katex>}}\frac{1}{2},\frac{1}{4},\frac{1}{8},\frac{1}{16}{{</katex>}}

and intuitively felt that “its sum” is 1 (in the cake problem). Actually in the cake problem, the stage by stage availability of the cake in the plate B is given in the following sequence.
{{<katex>}}\frac{1}{2},\frac{1}{4},\frac{1}{8},\frac{1}{16}...{{</katex>}}·
The n<sup>th</sup> term of this sequence is
{{<katex>}}\frac{1}{2},\frac{1}{4},\frac{1}{8},\frac{1}{16} · · · \frac{1}{2}<sup>n</sup>{{</katex>}}
which is equal to 2
n−1
2n . If sn denote this sum, then limn→∞
sn = 1. This is one of the reasons for us to
feel that the sum

{{<katex>}}\frac{1}{2},\frac{1}{4},\frac{1}{8},\frac{1}{16} + · · · {{</katex>}}is 1.

Motivated by this we may define the sum of infinitely many numbers. Let (an) be a sequence of real numbers and let sn = {{<katex>}}a_{1}+a_{2}+a_{3}+...... +a_{n}{{</katex>}}. If the sequence (sn) converges to a limit s, then it is meaningful to say that the sequence (an) is “summable” and the sum is s. In this case, we write

{{<katex>}}a_{1}+a_{2}+a_{3}+...... {{</katex>}}= s

It is customary to say that the series converges to s.

We write {{<katex>}}\sum_{n=1}^{∞}{{</katex>}}
an = s. 

Let us see some examples. The series
 {{<katex>}}\sum_{n=1}^{∞}{{</katex>}}
(−1)<sup>n+1</sup> does not converge because the partial sum sequence 1, 0, 1, 0, 1, 0, . . . does not converge.
We cannot apply algebraic rules meant for finite series to an infinite series blindly.
Consider
 {{<katex>}}\sum_{n=1}^{∞}{{</katex>}}(−1)<sup>n+1</sup>= 1 − 1 + 1 − 1 + · · · If S = 1 − 1 + 1 − 1 + · · · then one
may argue that S = 0 or 1 or {{<katex>}}\frac{1}{2}{{</katex>}}
according to S = (1 − 1) + (1 − 1) + · · · ,
S = 1 + (−1 + 1) + (−1 + 1) + · · · or 1 − S = 1 − (+1 − 1 + 1 − 1 + · · · = S)
respectively.

The series
∞
Σ
n=0
x
n
converges if x =
1
2 whereas it does not converge if x = 2. This shows that series like
∞
Σ
n=0
anx
n
converges for some values of x and does not converge for some values of x. The problem of
finding the values of x for which sequences of this form converges is beyond the scope of this book.
However in the rest of the chapter we list some series with the appropriate values of x for which the
series converges and the sum of the series whenever it converges.

**5.6.2 Infinite Geometric Series**
The series Σx<sup>n</sup> is called a geometric series or geometric progression. Let us start with the series:
∞
Σ
n=0
x
n
, x 6= 1. If sn = x0 + x1 + x2 + · · · + xn, then sn =
1−x
n
1−x
. As x
n
tends to 0 if |x| < 1, we say
that sn tends to 1
1−x
if |x| < 1.
•
∞
Σ
n=0
x
n
converges for all real number x with |x| < 1 and the sum is 1
1−x
. That is, for all real
numbers x satisfying |x| < 1,
1
1 − x
= 1 + x + x
2 + x
3 + · · ·
•
∞
Σ
n=0
(−1)nx
n
converges for all real number x with |x| < 1 and the sum is 1
1+x
. That is, for all real
numbers x satisfying |x| < 1,
1
1 + x
= 1 − x + x
2 − x
3 + · · ·
•
∞
Σ
n=0
(2x)
n
converges for all real number x with |x| <
1
2
and the sum is 1
1−2x
. That is, for real
numbers x satisfying |x| <
1
2
,
1
1 − 2x
= 1 + 2x + 4x
2 + 8x
3 + · · ·
•
∞
Σ
n=0
x
n
n!
converges for all real number x and the sum is e
x
. That is,
e
x = 1 +
x
1! +
x
2
2! +
x
3
3! +
x
4
4! + · · ·
for all real numbers x.
•
∞
Σ
n=0
(−1)nx converges only for x = 0.
Let us discuss some special series. By assuming the convergence of those series let us solve some
problems.
5.6.3 Infinite Arithmetico-Geometric Series
• The sum of the arithmetico-Geometric series Σ((a + (n − 1)d))r
n−1
is given by
S = limn→∞
Sn =
a
1 − r
+
dr
(1 − r)
2
for −1 < r < 1.