---
title: 'Basic Rules of Integration'
weight: 3
---

# 3 Basic Rules of Integration

**Standard results**

Since integration is the reverse process of differentiation, the basic integration formulae given
below can be derived directly from their corresponding derivative formulae from earlier chapter.

| Derivatives | Antiderivatives |
|------|------|
| {{< katex >}} \frac{dx}{dy} {{< /katex >}} (C)=0 , where c is a constant | ∫0dx=c , where c is a constant |
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(kx) =k, where k is a constant | ∫k dx = kx+c , where c is a constant|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(logx)=(1/x)|∫{{< katex >}} \frac{1}{x} {{< /katex >}} dx=logx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}} (-cosx) = sinx|∫sinx dx =-cos x+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}} (sinx)= cosx|∫cosx dx=sinx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}} (tanx)= secx|∫secx dx=tanx +c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(-cotx)=cosecx|∫cosecx dx=-cotx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(secx)=sedx tanx|∫secx tanx dx = secx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(-cosecx)=cosecx cotx|∫cosecx cotx dx=-cosecx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(e^{x})={{_{a}}^{x}}|∫e dx=e+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}({{< katex >}} \frac{{_{a}}^{x}}{loga} {{< /katex >}})=a|∫a dx={{< katex >}} \frac{a}{loga} {{< /katex >}}+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}({_{sinx}}^{-1})={{< katex >}} \frac{1}{\sqrt[]{}1-x}{{< /katex >}}|∫({{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}})dx =sinx+c|
|{{< katex >}} \frac{d}{dx} {{< /katex >}}(tanx)=({{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}})|∫({{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}})dx=tanx+c|

**Example 11.1**

Integrate the following with respect to x.


     (i)10      (ii)1/x    (iii) x     (iv) 1

**solution** 

   (i)  We know that ∫ x dx = {{< katex >}} \frac{x}{n+1} {{< /katex >}}+c, n=-1.

   Putting n =10, we get

   ∫x dx = {{< katex >}} \frac{x}{-10+1} {{< /katex >}}+c=-{{< katex >}} \frac{x}{11} {{< /katex >}}+c

   (ii)∫{{< katex >}} \frac{1}{x} {{< /katex >}} dx =∫x dx = {{< katex >}} \frac{x}{-10+1} {{< /katex >}}+c=-{{< katex >}} \frac{x}{11} {{< /katex >}}+c

   (iii)∫{{< katex >}} \frac{1}{\sqrt[]{}x} {{< /katex >}} dx = ∫ {{< katex >}} \frac{x}{1/2} {{< /katex >}} 

**Example 11.2**

Integrate the following with respect to x

 (i) 2/cos x    (ii) cotx/sinx    (iii) sinx /cosx    (iv) {{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}}

 **solution**

(i) ∫{{< katex >}} \frac{1}{cosx} {{< /katex >}} = ∫ secx xdx= tanx+c 

(ii) ∫{{< katex >}} \frac{cotx}{sinx} {{< /katex >}}dx = ∫cosecxcotx dx = -cosecx+c

(iii)∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}dx= ∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}.{{< katex >}} \frac{1}{cosx} {{< /katex >}}dx = ∫tanxsecx dx = secx +c

(iv) ∫{{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}} dx = sinx+c

**Example 11.3**

Integrate the following with respect to x:

(i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}

**solution**

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

   **EXERCISE 11.1**

   Integrate the following with respect to x:

(1) (i) x{{< katex >}}^{11}{{< /katex >}}           (ii)1/x{{< katex >}}^{7}{{< /katex >}}
(iii) {{< katex >}}\sqrt[3]{x}{{< /katex >}} {{< katex >}}^{4}{{< /katex >}}   (iv)(x{{< katex >}}^{5}{{< /katex >}}) {{< katex >}}^{1/8}{{< /katex >}} 

(2) (i)1/sin{{< katex >}}^{2}{{< /katex >}}x   (ii) {{< katex >}} \frac{tanx}{cosx} {{< /katex >}} 
     (iii)  {{< katex >}} \frac{cosx}{sinx} {{< /katex >}}  (iv)1/cos{{< katex >}}^{2}{{< /katex >}}x
     
(2) (i) 12{{< katex >}}^{3}{{< /katex >}} (ii) x{{< katex >}}^{23}{{< /katex >}}/x{{< katex >}}^{25}{{< /katex >}}
     (iii) e{{< katex >}}^{x}{{< /katex >}}
     
(2) (i) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}} (ii) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}}
                                             