---
title: 'Sets'
weight: 1
---
# Sets

In the earlier classes, we have seen that a set is a collection of well-defined objects. As the theory of
sets is the building blocks of modern mathematics, one has to learn the concepts of sets carefully and
deeply. Now we look at the term “well-defined” a little more deeply. Consider the two statements:
>(i) The collection of all beautiful flowers in Ooty Rose Garden.

>(ii) The collection of all old men in Tamilnadu.

The terms “beautiful flowers” and “old men” are not well-defined. We cannot define the term
“beautiful flower” in a sharp way as there is no concrete definition for beauty because the concept of
beauty varies from person to person, content to content and object to object. We should not consider
statements like “the collection of all beautiful flowers in Ooty Rose Garden” as a set. Now, can we
say “the collection of all red flowers in Ooty Rose Garden” a set? The answer is “yes”.

One may consider a person of age 60 as old and others may not agree. There is no specific and
concrete definition for “old men”. The second statement can be made more sharply as
“the collection of all men in Tamilnadu of age greater than 70”.
Now, the above collection becomes a set because of definiteness in the age. Thus, the description of
a set should enable us to concretely decide whether a given particular object (element) is available in
the collection or not. So set is a distinguishable collection of objects.
We have also seen and learnt to use symbols like ∈, ⊂, ⊆, ∪ and ∩. Let us start with the question:
>“If A and B are two sets, is it meaningful to write A ∈ B?”

At the first sight one may hurry to say that this is always meaningless by telling, “the symbol ∈
should be used between an element and a set and it should not be used between two sets”. The first
part of the statement is true whereas the second part is not true. For example, if A = {1, 2} and
B = {1, {1, 2}, 3, 4}, then A ∈ B. In this section we shall discuss the meaning of such symbols more
deeply.

As we learnt in the earlier classes the set containing no elements is called an <span style="color:brown">***empty set***</span>. or a  <span style="color:brown">***void set***</span>. It is usually denoted by ∅ or { }. By A ⊆ B, we mean every element of the set A is an element of
the set B. In this case, we say A is a  <span style="color:brown">***subset***</span> of B and B is a  <span style="color:brown">***super set***</span> of A. For any two sets A and
B, if A ⊆ B and B ⊆ A, then the two sets are  <span style="color:brown">***equal***</span>. For any set A, the empty set ∅ and the set A are
always subsets of A. These two subsets are called  <span style="color:brown">***trivial subsets***</span>. Further, we say A is a  <span style="color:brown">***proper subset***</span>
of B if A is a subset of B and A 6= B. That is, B contains all elements of A and at least one element
which is not in A. Note that, as every element of A is an element of A, we have A ⊆ A. Thus, any
set is a subset of itself. This subset is called an  <span style="color:brown">***improper subset***</span>. In other words, for any set A, A is
the improper subset of A. It is known that, N ⊂ W ⊂ Z ⊂ Q ⊂ R, where N denotes the set of all
natural numbers or positive integers, W denotes the set of all non-negative integers, Z denotes the set
of all integers, Q denotes the set of all rational numbers and R denotes the set of all real numbers.
Note that, the set of all irrational numbers is a subset of R but not a subset of any other set mentioned
above.

We learnt that the <span style="color:brown">***union***</span> of two sets A and B is denoted by A ∪ B and is defined as
>A ∪ B = {x : x ∈ A or x ∈ B}

and the <span style="color:brown">***intersection***</span> as
>A ∩ B = {x : x ∈ A and x ∈ B}.

Two sets A and B are <span style="color:brown">***disjoint***</span> if they do not have any common element. That is, A and B are
disjoint if A ∩ B = ∅.

Let us see some more notations. We are familiar with notations like {{<katex>}}\sum_{i=1}^n a_i{{</katex>}}
. This in fact stands for
a<sub>1</sub> + a<sub>2</sub> + · · · + a<sub>n</sub>. Similarly we can use the notations {{<katex>}}\cup_{i=1}^n a_i{{</katex>}} {{<katex>}}\cap_{i=1}^n a_i{{</katex>}} to denote A<sub>1</sub> ∪ A<sub>2</sub> ∪ · · · ∪ A<sub>n</sub>
and A<sub>1</sub> ∩ A<sub>2</sub> ∩ · · · ∩ A<sub>n</sub> respectively.

Thus, placeholder . These notations are 
useful when we discuss more number of sets.

If A is a set, then the set of all subsets of A is called the <span style="color:brown">***power set***</span> of A and is usually denoted
as P(A). That is, P(A) = {B : B ⊆ A}. The number of elements in P(A) is 2
n
, where n is the
number of elements in A.

Now, to define the complement of a set, it is necessary to know about the concept of universal
set. Usually all sets under consideration in a mathematical process are assumed to be subsets of some
fixed set. This basic set is called the <span style="color:brown">***universal set***</span>. For example, depending on the situation, for the set
of prime numbers, the universal set can be any one of the sets containing the set of prime numbers.
Thus, one of the sets N, W, Z, Q, R may be taken as a universal set for the set of prime numbers,
depending on the requirement. Universal set is usually denoted by U.
To define the <span style="color:brown">***complement***</span> of a set, we have to fix the universal set. Let A be a subset of the
universal set U.

 The complement of A with respect to U is denoted as A' or A<sup>c</sup>
and defined as
>A<sub>0</sub> = {x : x ∈ U and x  {{<katex>}}\not\in{{</katex>}} A}.
The <span style="color:brown">***set difference***</span> of the set A to the set B is denoted by either A − B or A /B and is defined as
>A − B = {a : a ∈ A and a /∈ B}.
Note that,
>(i) U − A = A0
>(ii) A − A = ∅ (iii) ∅ − A = ∅ (iv) A − ∅ = A (v) A − U = ∅.

The <span style="color:brown">***symmetric difference***</span> between two sets A and B is denoted by A∆B and is defined as
A∆B = (A − B) ∪ (B − A). Actually the elements of A∆B are the elements of A ∪ B which
are not in A ∩ B. Thus A∆B = (A ∪ B) − (A ∩ B).
A set X is said to be a <span style="color:brown">***finite set***</span> if it has k elements for some k ∈ W. In this case, we say the
finite set X is of <span style="color:brown">***cardinality***</span> k and is denoted by n(X). A set is an <span style="color:brown">***infinite set***</span> if it is not finite. For
an infinite set A, the cardinality is infinity. If n(A) = 1, then it is called a <span style="color:brown">***singleton set***</span>. Note that
n(∅) = 0 and n({∅}) = 1.

**1.2.1 Properties of Set Operations**
<pre>
We now list out some of the properties.
Commutative
(i) A ∪ B = B ∪ A (ii) A ∩ B = B ∩ A.
Associative
(i) (A ∪ B) ∪ C = A ∪ (B ∪ C) (ii) (A ∩ B) ∩ C = A ∩ (B ∩ C).
Distributive
(i) A ∪ (B ∩ C) = (A ∪ B) ∩ (A ∪ C) (ii) A ∩ (B ∪ C) = (A ∩ B) ∪ (A ∩ C).
Identity
(i) A ∪ ∅ = A (ii) A ∩ U = A.
Idempotent
(i) A ∪ A = A (ii) A ∩ A = A.
Absorption
(i) A ∪ (A ∩ B) = A (ii) A ∩ (A ∪ B) = A
De Morgan Laws
(i) (A ∪ B)
0 = A0 ∩ B0
(ii) (A ∩ B)
0 = A0 ∪ B0
(iii) A − (B ∪ C) = (A − B) ∩ (A − C) (iv) A − (B ∩ C) = (A − B) ∪ (A − C).
On Symmetric Difference
(i) A∆B = B∆A (ii) (A∆B)∆C = A∆(B∆C)
(iii) A ∩ (B∆C) = (A ∩ B)∆(A ∩ C).
On Empty Set and Universal Set
(i) ∅
0 = U (ii) U
0 = ∅
(iii) A ∪ A0 = U (iv) A ∩ A0 = ∅
(v) A ∪ U = U (vi) A ∩ U = A.
On Cardinality
(i) For any two finite sets A and B, n(A ∪ B) = n(A) + n(B) − n(A ∩ B).
(ii) If A and B are disjoint finite sets, then n(A ∪ B) = n(A) + n(B).
(iii) For any three finite sets A, B and C,
n(A ∪ B ∪ C) = n(A) + n(B) + n(C) − n(A ∩ B) − n(A ∩ C) − n(B ∩ C) + n(A ∩ B ∩ C).
</pre>
