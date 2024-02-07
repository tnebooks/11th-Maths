---
title: 'Integrals of the form f '
weight: 4
---

# 4 Integrals of the form f

we know that 

{{< katex >}} \frac{d}{dx} {{< /katex >}}[{{< katex >}} \frac{(x-a)}{10} {{< /katex >}}] = (x-a){{< katex >}}^{9}{{< /katex >}} =>  ∫(x-a){{< katex >}}^{9}{{< /katex >}} dx = {{< katex >}} \frac{(x-a)}{10} {{< /katex >}}+c

{{< katex >}} \frac{d}{dx} {{< /katex >}}[sin(x+k)]=cos(x+k) => 
∫cos(x+k)dx=sin(x+k)+c

 It is clear that whenever a constant is added or subtracted with the independent variable x, the 
fundamental formulae remain the same.
     But

{{< katex >}} \frac{d}{dx} {{< /katex >}} [{{< katex >}} \frac{1}{l} {{< /katex >}}(e{{< katex >}}^{lx+m}{{< /katex >}})]= e{{< katex >}}^{lx+m}{{< /katex >}} => ∫ e{{< katex >}}^{lx+m}{{< /katex >}} dx = {{< katex >}} \frac{1}{l} {{< /katex >}}e({{< katex >}}^{lx+m}{{< /katex >}})+c

{{< katex >}} \frac{d}{dx} [{{< /katex >}}[{{< katex >}} \frac{1}{a} {{< /katex >}}sin(ax+b)]] = cos(ax+b) => ∫cos(ax+b)dx =  {{< katex >}} \frac{1}{a} {{< /katex >}} sin(ax+b)+c

Here, if any constant is multiplied with the independent variable x, then the same fundamental
formula can be used after dividing it by the coefficient of x

that is, if ∫f(x)dx = g(x)+c,
 then ∫f(ax+b)dx = {{< katex >}} \frac{1}{a}{{< /katex >}}g(ax+b)+c

 The above formula can also be derived by using substitution method, which will be studied later.

**Example 11.4**

Evaluate the following with respect to x:

 (i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx (ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx (iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx

 **Solution**

(i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx = {{< katex >}} \frac{1}{4} {{< /katex >}} {{< katex >}} \frac{4x+5}{6+1} {{< /katex >}} = {{< katex >}} \frac{(4x+5)}{28} {{< /katex >}}+c

(ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx = ∫(15-2x){{< katex >}}^{1/2}{{< /katex >}} dx 

(iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx = ∫(3x+7){{< katex >}}^{-4}{{< /katex >}}

**Example 11.5**

Integrate the following with respect to x

 (i) 2/cos x    (ii) cotx/sinx    (iii) sinx /cosx    (iv) {{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}}

 **solution**

(i) ∫{{< katex >}} \frac{1}{cosx} {{< /katex >}} = ∫ secx xdx= tanx+c 

(ii) ∫{{< katex >}} \frac{cotx}{sinx} {{< /katex >}}dx = ∫cosecxcotx dx = -cosecx+c

(iii)∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}dx= ∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}.{{< katex >}} \frac{1}{cosx} {{< /katex >}}dx = ∫tanxsecx dx = secx +c

(iv) ∫{{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}} dx = sinx+c

**Example 11.6**

Integrate the following with respect to x:

(i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}

**solution**

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

**Example 11.7**

Integrate the following with respect to x:

(i) e{{< katex >}}^{3x}{{< /katex >}}     (ii) e{{< katex >}}^{5-4x}{{< /katex >}}      (iii){{< katex >}} \frac{1}{3x-2} {{< /katex >}} 

**Solution**

(i) ∫e{{< katex >}}^{3x}{{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}  e{{< katex >}}^{3x}{{< /katex >}}+c

(ii) ∫e{{< katex >}}^{5-4x}{{< /katex >}} dx =  (-e{{< katex >}}^{5-4x}{{< /katex >}}/4) +c

(iii) ∫{{< katex >}} \frac{1}{3x-2} {{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}log|(3x-2)|+c

**EXERCISE 11.2**

    Integrate the following with respect to x:

(1) (i) x{{< katex >}}^{11}{{< /katex >}}           (ii)1/x{{< katex >}}^{7}{{< /katex >}}
(iii) {{< katex >}}\sqrt[3]{x}{{< /katex >}} {{< katex >}}^{4}{{< /katex >}}   (iv)(x{{< katex >}}^{5}{{< /katex >}}) {{< katex >}}^{1/8}{{< /katex >}} 

(2) (i)1/sin{{< katex >}}^{2}{{< /katex >}}x   (ii) {{< katex >}} \frac{tanx}{cosx} {{< /katex >}} 
     (iii)  {{< katex >}} \frac{cosx}{sinx} {{< /katex >}}  (iv)1/cos{{< katex >}}^{2}{{< /katex >}}x
     
(2) (i) 12{{< katex >}}^{3}{{< /katex >}} (ii) x{{< katex >}}^{23}{{< /katex >}}/x{{< katex >}}^{25}{{< /katex >}}
     (iii) e{{< katex >}}^{x}{{< /katex >}}
     
(2) (i) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}} (ii) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}}
                                             