---
title: 'Particular cases of Binomial theorem'
weight: 3
---

**5.3 Particular cases of Binomial Theorem**

(i) Replacing b by (−b), in the binomial expansion of (a + b)<sup>n</sup>, n ∈ N, we get
        (a − b)<sup>n</sup> = nC0 a<sup>n</sup>b<sup>0</sup> −nC1 a<sup>n-1</sup>b<sup>1</sup> +nC2 a<sup>n-2</sup>b<sup>2</sup> − · · ·+(−1)r nCr a<sup>n-r</sup>b<sup>r</sup> +··+ (−1)n nCn a<sup>0</sup>b<sup>n</sup>.

Observe that the sign ‘+’ and ‘−’ appear alternately in the binomial expansion of (a − b)n.

(ii) Replacing a by 1 and b by x, in the binomial expansion of (a + b)<sup>n</sup>, we get

(1 + x)<sup>n</sup> =nC0 +nC1 x +nC2 x<sup>2</sup> + · · · +nCr x<sup>r</sup> + · · · +nCn x<sup>n</sup>.

In particular, when x = 1, nC0 + nC1 + nC2 + · · · + nCn = 2n.

        If X is a set containing n elements, then we know that nCr is the number of subsets of X having exactly r elements. So by adding nCr for r = 0,1, 2, . . . , n
        we get the number of subsets of X. So by using the above identity we see that a set of n elements has 2n subsets.

(iii) (1 − x)<sup>n</sup> = nC0 − nC1 x + nC2 x2 − · · · + (−1)r nCr xr + · · · + (−1)nxn. In particular, 
when x = 1, nC0 + nC2 + nC4 + · · · = nC1 + nC3 + nC5 + · · · = 2n−1
                $$ C(n, r) = \binom{n}{r} = \frac{n!}{r! \cdot (n-r)!} $$


**Example 5.1**  Find the expansion of (2x + 3)<sup>5</sup>

**Solution :** 
By taking a = 2x, b = 3 and n = 5 in the binomial expansion of (a + b)<sup>n</sup>we get

    (2x + 3)5 = (2x)^{5} + 5(2x)3 + 10(2x)332 + 10(2x)233 + 5(2x)34 + 35
              =32x5 + 240x4 + 720x3 + 1080x2 + 810x + 243.



**Example 5.2**  Evaluate 98<sup>4</sup>.

**Solution :** 
By taking a = 100, b = 2 and n = 4 in the binomial expansion of (a − b)
<sup>n</sup> we get

    98^4 = (100 − 2)4
         = 4C0 1004 −4C1 10032 + 4C2 100222 −4C3 100123 +4C4 100024
         = 100000000 − 8000000 + 240000 − 3200 + 16
         = 92236816