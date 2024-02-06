---
title: "Quadratic functions"
weight: 4
---

# Quadratic Functions

In earlier classes we have learnt that for any {{< katex >}} z\in \mathbb{R} {{< /katex >}} and {{< katex >}} n\in \mathbb{N} {{< /katex >}}, {{< katex >}} z^{n} {{< /katex >}}= z · z · z · · · z (n-times).

A function of the form P(x) = {{< katex >}} ax^{2} {{< /katex >}} + bx + c, where a, b, {{< katex >}} c\in \mathbb{R} {{< /katex >}} are constants and a {{< katex >}} \neq {{< /katex >}} 0, is called a quadratic function. If P(t) = 0 for some {{< katex >}} t\in \mathbb{R} {{< /katex >}}, then we say t is a zero of P(x).

**2.5.1 Quadratic Formula**

Is it possible to write the general quadratic function P(x) = {{< katex >}} ax^{2} {{< /katex >}} + bx + c in the form P(x) = {{< katex >}} a(x-k)^{2} {{< /katex >}} + d? The answer is yes. We can do this by the
method called “completing the square.” We shall rewrite the function P(x) as follows:

P(x) = {{< katex >}} ax^{2} {{< /katex >}} + bx + c

= {{< katex >}} a(x^{2}+2x\tfrac{b}{2a}+\frac{c}{a}) {{< /katex >}}

= {{< katex >}} a(x^{2}+2x\tfrac{b}{2a}+(\frac{b}{a})^{2}-\frac{b^{2}}{4a^{2}}+\frac{c}{a}) {{< /katex>}}

= {{< katex >}} a(x+\frac{b}{2a})^{2}-a\frac{b^{2}}{4a^{2}}+\frac{c}{a} {{< /katex >}}

= {{< katex >}} a(x+\frac{b}{2a})^{2}+(a(\frac{b}{2a})^{2}-b\frac{b}{2a}+c) {{< /katex >}}

Thus, P(x) = {{< katex >}} a(x+\frac{b}{2a})^{2}+P(\frac{-b}{2a}) {{< /katex >}} . (1)

Now, to find the x- intercepts of the curve described by P(x), let us solve for P(x) = 0.

Considering P(x) = 0 from (1) it follows that a

{{< katex >}} a(x+\frac{b}{2a})^{2} = -P(\frac{-b}{2a}) {{< /katex >}}

={{< katex >}} -\frac{(-b^{2}+4ac)}{4a} {{< /katex >}}

{{< katex >}} (x+\frac{b}{2a})^{2} {{< /katex >}} = {{< katex >}} \frac{b^{2}-4ac}{4a^{2}} {{< /katex >}}.

So {{< katex >}} x = \frac{\sqrt{b^{2}-4ac}}{2a}-\frac{b}{2a} or x = -\frac{\sqrt{b^{2}-4ac}}{2a}-\frac{b}{2a} {{< /katex >}}

Hence, x = {{< katex >}}\frac{-b\pm \sqrt{b^{2}-4ac}}{2a} {{< /katex >}}; which is called the quadratic formula.

**Remark:**

(i) Note that {{< katex >}} \sqrt{u} {{< /katex >}} is defined as a real number only for u ≥ 0.

(ii) when we write {{< katex >}} \sqrt{u} {{< /katex >}}, we mean only the nonnegative root.

Note that P(x) = 0 has two distinct real solutions if {{< katex >}}b^{2}-4ac {{< /katex >}} > 0, the roots are real and equal if {{< katex >}}b^{2}-4ac {{< /katex >}} = 0, and no real root if {{< katex >}}b^{2}-4ac {{< /katex >}} < 0.

Thus the curve intersects x-axis in two places if {{< katex >}}b^{2}-4ac {{< /katex >}} > 0, touches x-axis at only one point if {{< katex >}}b^{2}-4ac {{< /katex >}} = 0, and does not intersect x-axis at any point if {{< katex >}}b^{2}-4ac {{< /katex >}} < 0.

That is why D = {{< katex >}}b^{2}-4ac {{< /katex >}} is called the discriminant of the quadratic function P(x) = {{< katex >}} ax^{2}+bx+c {{< /katex >}}.

(i) If α and β are roots of {{< katex >}} ax^{2}+bx+c {{< /katex >}} = 0, then α + β ={{< katex >}}\frac{-b}{a}{{< /katex >}} and αβ = {{< katex >}}\frac{c}{a}{{< /katex >}}.

(ii) If the discriminant {{< katex >}}b^{2}-4ac {{< /katex >}} is negative, then the quadratic equation
{{< katex >}} ax^{2}+bx+c {{< /katex >}} = 0, has no real roots. In this case, we have complex roots given by

α = {{< katex >}} \frac{-b+i\sqrt{4ac-b^{2}}}{2a} {{< /katex >}} , β = {{< katex >}} \frac{-b-i\sqrt{4ac-b^{2}}}{2a} {{< /katex >}} , where {{< katex >}} i^{2} {{< /katex >}} = −1,

which we will study in Higher Secondary Second year

(iii) For example, let us look at the graph of y = {{< katex >}} x^{2}-4x+5 {{< /katex >}}. (See Figure 2.4.)
Since the graph does not intersect the x−axis, {{< katex >}} x^{2}-4x+5 {{< /katex >}} = 0 has no real roots.

(iv) We have the following table describing the nature of the roots of a quadratic
equation and the sign of the discriminant D = {{< katex >}}b^{2}-4ac {{< /katex >}}.

**2.5 Quadratic Functions**

Figure 2.4

| Discriminant | Nature of roots   | Parabola                        |
| ------------ | ----------------- | ------------------------------- |
| Positive     | real and distinct | intersects x-axis at two points |
| Zero         | real and equal    | touches x-axis at one point     |
| Negative     | no real roots     | does not meet x-axis            |

---

**Example 2.10** If a and b are the roots of the equation {{< katex >}} x^{2}-px+q {{< /katex >}} = 0, find the value of {{< katex >}} \frac{1}{a} + \frac{1}{b} {{< /katex >}} .

Solution:

Given that a and b are the roots of {{< katex >}} x^{2}-px+q {{< /katex >}} = 0. Then, a + b = p and ab = q. Thus, {{< katex >}} \frac{1}{a} + \frac{1}{b} {{< /katex >}} = {{< katex >}} \frac{a+b}{ab} {{< /katex >}} = {{< katex >}} \frac{p}{q} {{< /katex >}}.

---

**Example 2.11** Find the complete set of values of a for which the quadratic {{< katex >}} x^{2}-ax+a+2 {{< /katex >}} = 0 has equal roots.

Solution:

The quadratic equation {{< katex >}} x^{2}-ax+a+2 {{< /katex >}} = 0 has equal roots.
So, its discriminant is zero. Thus, D = {{< katex >}} b^{2}-4ac {{< /katex >}}c = {{< katex >}} a^{2}-4a+8 {{< /katex >}} = 0.
So, a = {{< katex >}} \frac{4\pm \sqrt{48}}{2} {{< /katex >}} which gives a = {{< katex >}} 2+\sqrt{12} {{< /katex >}}, {{< katex >}} 2-\sqrt{12} {{< /katex >}}

---

**Example 2.12** Find the number of solutions of {{< katex >}} x^{2}+|x-1| {{< /katex >}}= 1.

Solution:
Case (1). For x ≥ 1, |x − 1| = x − 1.

Then the given equation reduces to {{< katex >}} x^{2}+x+2 {{< /katex >}} = 0. Factoring we get (x+2)(x−1) = 0, which implies x = −2 or 1. As x ≥ 1, we obtain x = 1.

Case (2). For x < 1, |x − 1| = 1 − x

Then the given equation becomes {{< katex >}} x^{2}+1-x {{< /katex >}} = 1. Thus we have x(x − 1) = 0 which
implies x = 0 or x = 1. As x < 1, we have to choose x = 0.

Thus, the solution set is {0, 1}. Hence, the equation has two solutions.

---

**Exercise - 2.4**

1. Construct a quadratic equation with roots 7 and −3.

2. A quadratic polynomial has one of its zeros 1 + {{< katex >}} \sqrt{5} {{< /katex >}} and it satisfies p(1) = 2. Find the quadratic polynomial.

3. If α and β are the roots of the quadratic equation {{< katex >}} x^{2}+\sqrt{2}x+3 {{< /katex >}}= 0, form a quadratic polynomial with zeroes {{< katex >}} \frac{1}{\alpha }, \frac{1}{\beta } {{< /katex >}}.

4. If one root of k(x − 1)2 = 5x − 7 is double the other root, show that k = 2 or −25.

5. If the difference of the roots of the equation {{< katex >}} 2x^{2}-(a+1)x+a-1 {{< /katex >}} = 0 is equal to their product, then prove that a = 2.

6. Find the condition that one of the roots of {{< katex >}} ax^{2}-bx+c {{< /katex >}} may be (i) negative of the other, (ii) thrice the other, (iii) reciprocal of the other.

7. If the equations {{< katex >}} x^{2}-ax+b {{< /katex >}} = 0 and {{< katex >}} x^{2}-ex+f {{< /katex >}}f = 0 have one root in common and if the secondnequation has equal roots, then prove that ae = 2(b + f).

8. Discuss the nature of roots of (i){{< katex >}} -x^{2}+3x+1 {{< /katex >}} = 0, (ii) {{< katex >}} 4x^{2}-x-2 {{< /katex >}} = 0, (iii) {{< katex >}} 9x^{2}+5x {{< /katex >}} = 0.

9. Without sketching the graphs, find whether the graphs of the following functions will intersect the x-axis and if so in how many points.
   (i) y = {{< katex >}} x^{2}+x+2 {{< /katex >}}, (ii) y = {{< katex >}} x^{2}-3x-7 {{< /katex >}}, (iii) y = {{< katex >}} x^{2}+6x+9 {{< /katex >}}.

10. Write f(x) = {{< katex >}} x^{2}+5x+4 {{< /katex >}} in completed square form.

**2.5.2 Quadratic Inequalities**

Here we shall learn to solve the quadratic inequalities {{< katex >}} ax^{2}+bx+c {{< /katex >}} < 0 or {{< katex >}} ax^{2}+bx+c {{< /katex >}} > 0.

**Steps to Solve Quadratic Inequalities:**

(i) First solve {{< katex >}} ax^{2}+bx+c {{< /katex >}} = 0.

(ii) If there are no real solutions, then one of the above inequality holds for all x ∈ R

(iii) If there are real solutions, which are called critical points, then label those points on the number
line.

(iv) Note that these critical points divide the number line into disjoint intervals. (It is possible that
there may be only one critical point.)

(v) Choose one representative number from each interval.

(vi) Substitute that these representative numbers in the inequality.

(vii) Identify the intervals where the inequality is satisfied.

**Example 2.13** Solve {{< katex >}} 3x^{2}+5x-2 {{< /katex >}} ≤ 0.

Solution:

On factorizing the quadratic polynomial we get 3(x + 2){{< katex >}} (x-\frac{1}{3}) {{< /katex >}} ≤ 0. Draw the number line. Mark the critical points −2 and {{< katex >}} \frac{1}{3} {{< /katex >}} where the factors vanish (See Figure 2.5). On each sub-interval check
the sign of (x + 2){{< katex >}} (x-\frac{1}{3}) {{< /katex >}}. To do this pick an arbitrary point anywhere in the interval. Whatever sign the resulting value has, the polynomial has the same sign throughout the whole corresponding
interval. (Otherwise, there would be another critical point within the interval). This process is easily
organized in the following table.

Figure 2.5

| Interval  | Sign of (x + 2) | Sign of (x − 1/3) | Sign of {{< katex >}} 3x^{2}+5x-2 {{< /katex >}} |
| --------- | --------------- | ----------------- | ------------------------------------------------ |
| (−∞, −2)  | -               | -                 | +                                                |
| (−2, 1/3) | +               | -                 | -                                                |
| (1/3, ∞)  | +               | +                 | +                                                |

You can see the inequality is satisfied in [−2, 1/3].

---

**Example 2.14** Solve {{< katex >}} \sqrt{x+14} {{< /katex >}} < x + 2.

Solution:

The function {{< katex >}} \sqrt{x+14} {{< /katex >}} is defined for x + 14 ≥ 0. Therefore x ≥ −14, x + 2 > 0 implies x ≥ −2.
(x + 14) < {{< katex >}} (x+2)^{2} {{< /katex >}} gives {{< katex >}} x^{2}+3x-10 {{< /katex >}} > 0.
Hence, (x + 5)(x − 2) > 0. Dividing the number line with the critical points x = −5 and x = 2.
Substituting a reference point in the sub-interval we get the solution set to be x < −5 and x > 2.
Since x ≥ −2, we have the solution to be x > 2.

---

**Example 2.15** Solve the equation {{< katex >}} \sqrt{6-4x-x^{2}} {{< /katex >}} = x + 4.

Solution:

The given equation is equivalent to the system (x + 4) ≥ 0 and {{< katex >}} 6-4x-x^{2} {{< /katex >}} = {{< katex >}} (x+4)^{2} {{< /katex >}}.
This implies x ≥ −4 and {{< katex >}} x^{2}+6x+5 {{< /katex >}} = 0. Thus, x = −1, −5.
But only x = −1 satisfies both the conditions. Hence, x = −1.

**Exercise - 2.5**

1. Solve {{< katex >}} 2x^{2}+x-15 {{< /katex >}} ≤ 0.

2. Solve {{< katex >}} -x^{2}+3x-2 {{< /katex >}} ≥ 0.
