---
title: 'Finite sequences'
weight: 4
---

**5.4 Finite Sequences**

A sequence is a list of elements with a particular order. While the idea of a sequence of numbers, a1, a2, · · · , is straight forward, it is useful to think of a sequence as a function whose domain is either
the set of first n natural numbers or N. Throughout this chapter, we consider only sequences of real numbers and we will refer to them as sequences. The arithmetic sequences and geometric sequences are also known as arithmetic progressions(AP) and geometric progressions (GP). Let us recall, the basic definitions of sequences and series.

• If X is any set and n ∈ N, then any function f : {1, 2, 3, . . . , n} → X is called a  {{<katex>}}\textbf{finite sequence} {{</katex>}}
on X and any function g : N → X is called an {{<katex>}}\textbf{infinite sequence} {{</katex>}}on X. The value f(n) of the
function f at n is denoted by an and the sequence itself is denoted by ({{<katex>}}a_{n}{{</katex>}}).

• If the set X happens to be a set of real numbers, the sequence is called a numerical sequence or a
sequence of real numbers.

• Though every sequence is a function, a function is not necessarily a sequence.

• Unlike sets, where elements are not repeated, the terms in a sequence may be repeated. In
particular, a sequence in which all terms are same is called a constant sequence.

• A useful way to visualise a sequence ({{<katex>}}a_{n}{{</katex>}}). is to plot the graph of {(n, {{<katex>}}a_{n}{{</katex>}}) : n ∈ N} which gives some details about the sequence.

**5.4.1 Arithmetic and Geometric Progressions**
Progressions are some special cases of sequences where the terms of the sequences are either in increasing form or decreasing form.
    We recall some definitions and results which has been discussed in earlier classes on arithmetic and geometric progressions.

**Arithmetic Progression (AP)**
• A sequence of the form

        a, a + d, a + 2d, a + 3d, . . . , a + (n − 1)d, a + nd, . . .

is called an arithmetic progression or an arithmetic sequence. In other words, each term (other
than the first term) of the sequence is obtained by adding a constant to its previous term; the
constant d is called common difference and the term a is called the initial term or first term.
• The nth term of an arithmetic progression is given by Tn = a + (n − 1)d.
• The sequences √2,√2 + √3,√2 + 2√3,√2+3√3, . . . and 12, 9, 6, 3, . . . are arithmetic sequences with common differences √3 and −3 respectively.
• It is interesting to observe that 3, 7, 11 are three prime numbers which form an AP.


• For n ∈ N, Tn = an + b where a and b are relatively prime, form an AP which contains infinitely many prime numbers along with infinitely many composite numbers.

**Geometric Progression (GP)**

• A sequence of the form

    a, ar, ar2, ar3, . . . , arn−1, arn, . . .

with a 6= 0, and r 6= 0 is called a geometric progression or a geometric sequence. In other words, each term (other than the first term) of the sequence is obtained by multiplying its previous term by a constant; the constant r is called common ratio and the term a is called the initial term or first term.

• The nth term of a geometric progression is given by Tn = arn−1.
• The sequences 1, 2, 4, 8, 16, . . . and √
2, 2, 2√2, 4, 4√2, 16, . . . are geometric sequenceswith common ratios 2 and √2 respectively.

• Taking logarithm of each term in a geometric progression with positive common ratio yields an arithmetic progression. i.e., If a, ar, ar2 , . . . is a GP with r > 0, then log a, log(ar), log(ar2), . . .
is an AP with common difference log r. It is interesting to note that the constant sequence c, c, c, . . . is an arithmetic sequence and is also a geometric sequence if c 6= 0.
Let us consider the special constant sequence 0, 0, 0, 0, . . . . We have no problem in seeing this as an arithmetic sequence. But when we try to see this as a geometric sequence clearly the initial term a must be 0. What can we say about the common ratio r? If we take r as 1, 2 or any other number we get the same sequence 0, 0, 0, 0, . . . . We are left with the situation where a geometric sequence has infinitely many common ratios. To overcome these confusions some mathematicians exclude this sequence from the class of geometric sequences by assuming a 6= 0 in the definition. (We made this assumption)

**5.4.2 Arithmetico-Geometric Progression (AGP)**
Combining arithmetic and geometric progressions, a new progression called arithmetico geometric progression is formed. As we use the abbreviations AP and GP for arithmetic progressions and geometric progressions, we use the abbreviation AGP for arithmetico geometric progression. AGP’s arise in various applications, such as the computation of expected value in probability theory.

**Definition 5.1**
A sequence of the form
a, (a + d)r, (a + 2d)r2, (a + 3d)r3, . . . , (a + (n − 1)d)rn−1, (a + nd)rn, . . .
is called an arithmetico-geometric progression or an arithmetico-geometric sequence.

Consider an AP: a, a + d, a + 2d, . . .
            GP: 1, r, r2, . . .
Then the AGP is a,(a + d)r,(a + 2d)r2, . . .
Here, a is the initial term, d is the common difference and r is the common ratio of the AGP.
If we take r = 1, then the AGP will become an AP and if we take d = 0, then it will become
a GP. So the arithmetic and Geometric progressions become particular cases of AGP. This is a nice
situation to know the concept of generalization in mathematics.

**5.4.3 Harmonic Progression (HP)**

Harmonic progression is one of many important sequences and is closely related to the arithmetic progression. Harmonic progression is widely used.

Definition 5.2
A sequence h1, h2, h3, . . . is said to a harmonic sequence or a harmonic progression if 1/h1,1/h2,1/h3,1/h4
, . . . is an arithmetic sequence.

Note that a sequence is in harmonic progression if reciprocal of its term are in arithmetic progression.
But we should not say that harmonic progressions are reciprocals of arithmetic progressions; in fact,
if an arithmetic sequence contains a zero term, then its reciprocal is not meaningful. Of course, if
an arithmetic progression contains no zero term, then its reciprocal is a harmonic progression. So a
general harmonic progression will be of the form