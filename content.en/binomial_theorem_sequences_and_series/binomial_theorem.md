---
title: 'Binomial theorem'
weight: 2
---

# 5.2 Binomial Theorem
The prefix bi in the words bicycle, binocular, binary and in many more words means two. The word
binomial stands for expressions having two terms. For examples (1 + x), (x + y), (x<sup>2</sup> + xy) and (2a + 3b) are some binomial expressions

**5.2.1 Binomial Coefficients**

In Chapter 4 we have learnt and used the symbol nCr which is defined as

Since nCr occurs as the coefficients of x<sup>r</sup>
in (1 + x)<sup>n</sup> n ∈ N and as the coefficients of a<sup>r</sup>
b<sup>n−r</sup> in (a + b)<sup>n</sup>, they are called binomial coefficients. Though the values of nCr can be computed by
formula, there is an interesting simple way to find nCr without doing cumbersome multiplications.

**Pascal Triangle**

The Pascal triangle is an arrangement of the values of nCr in a triangular form. The (k + 1)<sup>st</sup> row consists values of

kC0 ,kC1 ,kC2 ,kC3 , . . . ,kCk .

In fact, the Pascal triangle is

Recall the expansion and observe the coefficients of each term of the identities (a + b)<sup>0</sup>, (a + b)<sup>1</sup>,(a + b)<sup>2</sup>, (a + b)<sup>3</sup>. There is a pattern in the arrangements of coefficents
            (a + b)<sup>0</sup> = 1 
            (a + b)<sup>1</sup> = a+b
            (a + b)<sup>2</sup> = a<sup>2</sup>+2ab+b<sup>2</sup>
            (a + b)<sup>3</sup> = a<sup>3</sup>+3a<sup>2</sup>b+3ab<sup>2</sup>+b<sup>3</sup>



If we observe carefully the Pascal triangle, we may notice that each row starts and ends with 1 and other entries are the sum of the two numbers just above it. For example ‘3’ is the sum of 1 and 2 above it; ‘10’ is the sum of 4 and 6 above it. We will prove in a short while that

(a + b)<sup>n</sup> =nC0 a n
b
0 +
nC1 a
n−1
b
1 + · · · +
nCr a
n−r
b
r + · · · +
nCn a
0
b
n
.

which is the binomial expansion of (a + b)n. The binomial expansion of (a + b)n for any n ∈ N can be written using Pascal triangle. For example, from the fifth row we can write down the expansion of(a + b)4
and from the sixth row we can write down the expansion of (a + b)5
and so on. We know the terms (without coefficients) of (a + b)<sup>5</sup> are
a<sup>5</sup>, a<sup>4</sup>b, a<sup>3</sup>b<sup>2</sup>, a<sup>2</sup>b<sup>3</sup>, ab<sup>4</sup>, b<sup>5</sup>

and the sixth row of the Pascal triangle is

                        1  5  10  10  5  1.


Using these two we can write
(a + b)<sup>5</sup> = a<sup>5</sup> + 5a<sup>4</sup>b + 10a<sup>3</sup>b<sup>2</sup> + 10a<sup>2</sup>b<sup>3</sup> + 5ab<sup>4</sup> + b<sup>5</sup>

The Pascal triangle can be constructed using addition alone, without using any multiplication or division. So without multiplication we can write down the binomial expansion for (a + b)n
for any n ∈ N.
The above pattern resembling a triangle, is credited in the name of the
seventeenth century French Mathematician Blaise Pascal, who studied mathematical properties of this structure and used this
concept effectively in Probability Theory.

{{<katex>}}\textbf{ 5.2.2 Binomial theorem for positive integral index}{{</katex>}}

Now we prove the most celebrated theorem called Binomial Theorem.


    Theorem 5.1 (Binomial theorem for positive integral index): If n is any positive integer, then

(a + b)<sup>n</sup> =nC0 anb0 +nC1 an−1b1 + · · · +nCr an−rbr + · · · +nCn a0bn.

Proof. We prove the theorem by using mathematical induction. For any positive integer n, let P(n) be the statement

(a + b)<sup>n</sup> =nC0 anb0 +nC1 an−1b1 + · · · +nCr an−rbr + · · · +nCn a0bn.

Since

                        1C0 = 1 and 1C1 = 1,

the expression in the right hand side of P(1) is a<sup>1</sup>b<sup>0</sup> + a<sup>0</sup>b<sup>1</sup> which is same as a + b; the left hand sideis (a + b)<sup>1</sup>. 

Hence P(1) is true.
    We assume that for a positive integer k, P(k) is true. That is,
        (a + b)<sup>k</sup> =kC0 a<sup>k</sup>b<sup>0</sup> +kC1 a<sup>k−1</sup>b<sup>1</sup> + · · · +kCr a<sup>k−r</sup>b<sup>r</sup> + · · · +kCk a<sup>0</sup>b<sup>k</sup>.

Let us use the identity

                        nCr +nCr−1 =n+1Cr

