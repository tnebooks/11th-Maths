---
title: 'Methods of Integration'
weight: 7
---

# 7  Methods of Integration

Integration is not as easy as differentiation. This is first due to its nature. Finding a derivative of
a given function is facilitated by the fact that the differentiation itself has a constructive character. A derivative is simply defined as

{{<katex>}}{\lim_{\bigtriangleup x->0}}{{</katex>}} {{< katex >}} \frac{f(x+{\bigtriangleup}x)-f(x)}{{\bigtriangleup}x} {{< /katex >}}

Suppose we are asked to find the derivative of log x, we know in all details how to proceed in order
to obtain the result.             
When we are asked to find the integral of log x, we have no constructive method to find integral or
even how to start.                              
In the case of differentiation we use the laws of differentiation of several functions in order to find derivatives of their various combinations, like their sum, product, quotient, composition of functions etc.                     
There are very few such rules available in the theory of integration and their application is rather
restricted. But the significance of these methods of integration is very great.                   
In every case one must learn to select the most appropriate method and use it in the most convenient
form. This skill can only be acquired after long practice.                      
Already we have seen two important properties of integration. The following are the four important
methods of integrations.

(1) Integration by decomposition into sum or difference.                    
(2) Integration by substitution.                       
(3) Integration by parts                            
(4) Integration by successive reduction.                              

Here we discuss only the first three methods of integration and the other will be studied in higher
classes.

**11.7.1 Decomposition method**

Sometimes it is very difficult to integrate the given function directly. But it can be integrated after
decomposing it into a sum or difference of number of functions whose integrals are already known.
 
 For example (1-x{{< katex >}}^{3} {{< /katex >}}){{< katex >}} ^{2} {{< /katex >}}, {{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}}, cos5xsin3x, cos{{< katex >}} ^{dx} {{< /katex >}}x, {{< katex >}} \frac{e^{2x}-1}{e^{x}} {{< /katex >}}, do not have direct formulae
to integrate. But these functions can be decomposed into a sum or difference of functions, whose 
individual integrals are known. In most of the cases the given integrand will be any one of the 
algebraic, trigonometric or exponential forms, and sometimes combinations of these functions.

**Example 11.15**

Integrate the following with respect to x:

(i) (1-x{{< katex >}}^{3} {{< /katex >}}){{< katex >}} ^{2} {{< /katex >}}           (ii){{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}}

**Solution**

(i) ∫(1-x{{< katex >}}^{3} {{< /katex >}}){{< katex >}} ^{2} {{< /katex >}}  dx = ∫(1-2x{{< katex >}} ^{2} {{< /katex >}} + x{{< katex >}} ^{6} {{< /katex >}} )dx

= ∫dx-2∫x{{< katex >}} ^{3} {{< /katex >}} dx +∫x{{< katex >}} ^{6} {{< /katex >}} dx

=x{{< katex >}} \frac{x^{4}}{2} {{< /katex >}}+{{< katex >}} \frac{x^{7}}{7} {{< /katex >}}+c

(ii)         ∫{{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}} dx = ∫({{< katex >}} \frac{x^{2}}{x^{3}} {{< /katex >}}-{{< katex >}} \frac{x}{x^{3}} {{< /katex >}}+{{< katex >}} \frac{1}{x^3} {{< /katex >}})dx          

=∫{{< katex >}} \frac{1}{x} {{< /katex >}}dx -∫{{< katex >}} \frac{1}{x^{x}} {{< /katex >}}dx+∫{{< katex >}} \frac{1}{x^{3}} {{< /katex >}}dx. 

∫{{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}}dx =log|x|+{{< katex >}} \frac{1}{x} {{< /katex >}}-{{< katex >}} \frac{1}{2x^{2}} {{< /katex >}}+c

**Example 11.16**

Evaluate the following with respect to x:

 (i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx (ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx (iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx

 **Solution**

(i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx = {{< katex >}} \frac{1}{4} {{< /katex >}} {{< katex >}} \frac{4x+5}{6+1} {{< /katex >}} = {{< katex >}} \frac{(4x+5)}{28} {{< /katex >}}+c

(ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx = ∫(15-2x){{< katex >}}^{1/2}{{< /katex >}} dx 

(iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx = ∫(3x+7){{< katex >}}^{-4}{{< /katex >}}

**Example 11.17**

Integrate the following with respect to x

 (i) 2/cos x    (ii) cotx/sinx    (iii) sinx /cosx    (iv) {{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}}

 **solution**

(i) ∫{{< katex >}} \frac{1}{cosx} {{< /katex >}} = ∫ secx xdx= tanx+c 

(ii) ∫{{< katex >}} \frac{cotx}{sinx} {{< /katex >}}dx = ∫cosecxcotx dx = -cosecx+c

(iii)∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}dx= ∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}.{{< katex >}} \frac{1}{cosx} {{< /katex >}}dx = ∫tanxsecx dx = secx +c

(iv) ∫{{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}} dx = sinx+c

**Example 11.18**

Integrate the following with respect to x:

(i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}

**solution**

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

**Example 11.19**

Integrate the following with respect to x:

(i) e{{< katex >}}^{3x}{{< /katex >}}     (ii) e{{< katex >}}^{5-4x}{{< /katex >}}      (iii){{< katex >}} \frac{1}{3x-2} {{< /katex >}} 

**Solution**

(i) ∫e{{< katex >}}^{3x}{{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}  e{{< katex >}}^{3x}{{< /katex >}}+c

(ii) ∫e{{< katex >}}^{5-4x}{{< /katex >}} dx =  (-e{{< katex >}}^{5-4x}{{< /katex >}}/4) +c

(iii) ∫{{< katex >}} \frac{1}{3x-2} {{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}log|(3x-2)|+c

**Example 11.20**

Evaluate : ∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

={{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c

**Example 11.22**

Evaluate: ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx

**Solution**

∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

=∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

=∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

=tanx+(-cotx)+c

=tanx-cotx+c

**Example 11.23**

Evalute: ∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx

**Solution**

∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx = ∫2sin{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}dx =∫tan{{< katex >}} ^{2} {{< /katex >}}dx

=∫(sec{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}-1)dx = {{< katex >}} \frac{tan{\frac{x}{2}}}{\frac{1}{2}} {{< /katex >}}-x+c

=2tan{{< katex >}} \frac{x}{2} {{< /katex >}}-x+c.

**Example 11.24**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c

**Example 11.25**

Evaluate : ∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

={{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c

**Example 11.26**

Evaluate: ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx

**Solution**

∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

=∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

=∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

=tanx+(-cotx)+c

=tanx-cotx+c

**Example 11.27**

Evalute: ∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx

**Solution**

∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx = ∫2sin{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}dx =∫tan{{< katex >}} ^{2} {{< /katex >}}dx

=∫(sec{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}-1)dx = {{< katex >}} \frac{tan{\frac{x}{2}}}{\frac{1}{2}} {{< /katex >}}-x+c

=2tan{{< katex >}} \frac{x}{2} {{< /katex >}}-x+c.

**Example 11.28**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c

**11.7.2 Decomposition by Partial Fractions**

One of the important methods to evaluate integration is partial fractions. If the 
integrand is in the form of an algebraic fraction and the integral cannot be evaluated by simple 
methods, then the fraction need to be expressed in partial fractions before integration takes 
place. We will assume that we have a rational function {{< katex >}} \frac{p(x)}{q(x)} {{< /katex >}},(q(x)=0) in which degree of 
p (x) < degree of q (x). If this is not the case, we can always perform long division.

**Example 11.29**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c


 **EXERCISE 11.3**

 Integrate the following with respect to x

 (1) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (2) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3) 

(4){{< katex >}} \frac{8}{\sqrt{1-4x{^{2}}}} {{< /katex >}}+ {{< katex >}} \frac{27}{\sqrt{1-9x{^{2}}}} {{< /katex >}} - {{< katex >}} \frac{15}{1-25x{^{2}}} {{< /katex >}}   

(5) {{< katex >}} \frac{6}{1+(3x+2){^{2}}} {{< /katex >}} - {{< katex >}} \frac{12}{\sqrt{1-(3-4x){^{2}}}} {{< /katex >}}       
        
(6){{< katex >}} \frac{1}{3} {{< /katex >}}cos({{< katex >}} \frac{x}{3} {{< /katex >}}-4)+{{< katex >}} \frac{7}{7x+9} {{< /katex >}}+e{{< katex >}} ^{{\frac{x}{5}+3}} {{< /katex >}}

(7) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3) 

(8){{< katex >}} \frac{8}{\sqrt{1-4x{^{2}}}} {{< /katex >}}+ {{< katex >}} \frac{27}{\sqrt{1-9x{^{9}}}} {{< /katex >}} - {{< katex >}} \frac{15}{1-25x{^{2}}} {{< /katex >}}   

(10) {{< katex >}} \frac{6}{1+(3x+2){^{2}}} {{< /katex >}} - {{< katex >}} \frac{12}{\sqrt{1-(3-4x){^{2}}}} {{< /katex >}}       
        
(11){{< katex >}} \frac{1}{3} {{< /katex >}}cos({{< katex >}} \frac{x}{3} {{< /katex >}}-4)+{{< katex >}} \frac{7}{7x+9} {{< /katex >}}+e{{< katex >}} ^{{\frac{x}{5}+3}} {{< /katex >}}

(12) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x^{2}}{8} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3) 

**11.7.3 Method of substitution or change of variable**

	 The method of substitution in integration is similar to finding the derivative of function of
function in differentiation. By using a suitable substitution, the variable of integration is changed to
new variable of integration which will be integrated in an easy manner.
	 We know that, if u is a function of x then {{< katex >}} \frac{du}{dx} {{< /katex >}}=u'.

Hence we can write ∫f(u)u'dx = ∫f(u)du

	 Thus,∫f[g(x)]g'(x)dx =  ∫f(u)du, where u=g(x)

	 The success of the above method depends on the selection of suitable substitution
u = g(x).

**Note 11.2**

The substitution for the variable of integration is in trigonometric function, use a rough
diagram to find the re -substitution value for it. Suppose the variable of integration x is substituted
as x = tanθ . After integration suppose the solution is secθ+cosecθ 

For example, if x= tan , then from 

cosecθ = ({{< katex >}} \frac{\sqrt{1+x^{2}}}{x} {{< /katex >}})

secθ  = ({{< katex >}} \frac{\sqrt{1+x^{2}}}{1} {{< /katex >}})

Then secθ+cosecθ  = ({{< katex >}} \sqrt{1+x^{2}}{{< /katex >}})+({{< katex >}} \frac{\sqrt{1+x^{2}}}{x} {{< /katex >}})

**Example 11.30**

Integrate the following with respect to x:

(i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}    (v) {{< katex >}} \frac{1}{3x-2} {{< /katex >}} 


**solution**

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

   (v)∫{{< katex >}} \frac{1}{3x-2} {{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}log|(3x-2)|+c

   **11.7.4 Important Results**

(1) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (2) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3) 

(4){{< katex >}} \frac{8}{\sqrt{1-4x{^{2}}}} {{< /katex >}}+ {{< katex >}} \frac{27}{\sqrt{1-9x{^{2}}}} {{< /katex >}} - {{< katex >}} \frac{15}{1-25x{^{2}}} {{< /katex >}}   

(5)log|f(x)|+c

   **Example 11.31**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c

**Example 11.32**

Evaluate : ∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

={{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c

**Example 11.33**

Evaluate: ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx

**Solution**

∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

=∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

=∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

=tanx+(-cotx)+c

=tanx-cotx+c


11.7.5 Integration by parts
Integration by parts method is generally used to find the integral when the integrand is a product
of two different types of functions or a single logarithmic function or a single inverse trigonometric
function or a function which is not integrable directly. From the formula for derivative of product of
two functions we obtain this useful method of integration.

If u and v are two differentiable functions then we have\

d(uv)=vdu+udv

udv=d(uv)-vdu

Integration,   
∫udv = ∫d(uv)-∫vdu

∫udv=uv-∫vdu

∫udv in terms of another integral ∫vdu and does not give a final expression for the integral
∫udv. It only partially solves the problem of integrating the product u dv . Hence the term ‘Partial
Integration’ has been used in many European countries. The term “Integration by Parts” is used in
many other countries as well as in our own.

The success of this method depends on the proper choice of u                    
(i) If integrand contains any non integrable functions directly from the formula, like logx,
tan−1
x etc., we have to take these non integrable functions as u and other as dv.                
(ii) If the integrand contains both the integrable function, and one of these is xn
 (where n is a
positive integer) then take u = xn.               
(iii) For other cases the choice of u is ours.

**Example 11.34**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c

**Example 11.35**

Evaluate : ∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

={{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c

**11.7.6 Bernoulli’s formula for Integration by Parts**

If u and v are functions of x, then the Bernoulli’s rule is
1 2 udv uv u v u v =− + − ′ ′′ ∫ 
where uu u ′ ′′ ′′′ , , ,... are successive derivatives of u and
v v, ,v v, , 1 2 3  are successive integrals of dv
Bernoulli’s formula is advantageously applied when n u x = ( n is a positive integer)
For the following problems we have to apply the integration by parts two or more times to find the
solution. In this case Bernoulli’s formula helps to find the solution easily.


**Example 11.36**

Evaluate: ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx

**Solution**

∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

=∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

=∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

=tanx+(-cotx)+c

=tanx-cotx+c


11.7.6 Bernoulli’s formula for Integration by Parts
If u and v are functions of x, then the Bernoulli’s rule is

 ∫ udv =uv-u'v{{< katex >}}_{1}{{< /katex >}}+u"v{{< katex >}}_{2}{{< /katex >}}------

where  u′,u′′,u′′′,... are successive derivatives of u and

v,v{{< katex >}}_{1}{{< /katex >}},v{{< katex >}}_{3}{{< /katex >}} are successive integrals of dv

Bernoulli’s formula is advantageously applied when u=x{{< katex >}}^{n}{{< /katex >}} ( n is a positive integer)
For the following problems we have to apply the integration by parts two or more times to find the
solution. In this case Bernoulli’s formula helps to find the solution easily.


**Example 11.35**

Integrate the following with respect to x:

(i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}

**solution**

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

   **EXERCISE 11.7**

   Integrate the following with respect to x:

(1) (i) x{{< katex >}}^{11}{{< /katex >}}           (ii)1/x{{< katex >}}^{7}{{< /katex >}}
(iii) {{< katex >}}\sqrt[3]{x}{{< /katex >}} {{< katex >}}^{4}{{< /katex >}}   (iv)(x{{< katex >}}^{5}{{< /katex >}}) {{< katex >}}^{1/8}{{< /katex >}} 

(2) (i)1/sin{{< katex >}}^{2}{{< /katex >}}x   (ii) {{< katex >}} \frac{tanx}{cosx} {{< /katex >}} 
     (iii)  {{< katex >}} \frac{cosx}{sinx} {{< /katex >}}  (iv)1/cos{{< katex >}}^{2}{{< /katex >}}x
     
(3) (i) 12{{< katex >}}^{3}{{< /katex >}} (ii) x{{< katex >}}^{23}{{< /katex >}}/x{{< katex >}}^{25}{{< /katex >}}
(iii) e{{< katex >}}^{x}{{< /katex >}}  (i) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}} (ii) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}}

**11.7.8 Integrals of the form**

The following examples illustrate that there are some integrals whose integration continues
forever. Whenever we integrate function of the form e{{< katex >}}^{ax}{{< /katex >}} cosbx or eax sinbx, we have to apply the
Integration by Parts rule twice to get the similar integral on both sides to solve.

**Example 11.36**

Evaluation: ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

=∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

=sinx-cosx+c

**EXERCISE 11.8**

   Integrate the following with respect to x:

(1) (i) x{{< katex >}}^{11}{{< /katex >}}           (ii)1/x{{< katex >}}^{7}{{< /katex >}}
(iii) {{< katex >}}\sqrt[3]{x}{{< /katex >}} {{< katex >}}^{4}{{< /katex >}}   (iv)(x{{< katex >}}^{5}{{< /katex >}}) {{< katex >}}^{1/8}{{< /katex >}} 

(2) (i)1/sin{{< katex >}}^{2}{{< /katex >}}x   (ii) {{< katex >}} \frac{tanx}{cosx} {{< /katex >}} 
     (iii)  {{< katex >}} \frac{cosx}{sinx} {{< /katex >}}  (iv)1/cos{{< katex >}}^{2}{{< /katex >}}x
    

**Example 11.37**

Evaluate : ∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

**Solution**

∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

={{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c

**EXERCISE 11.9**

(1) If f'(x)=4x-5 and f(2)=1, find f(x). 

(2) Iff'(x)=9x{{<katex>}}^{2}{{</katex>}}-6x and f(0)=-3, find f(x). 

(3) If f"(x)=12x-6 and f(1)=30, f'(1)=5 find f(x).         

**11.7.9 Integration of Rational Algebraic Functions**

In this section we are going to discuss how to integrate the rational algebraic functions whose 
numerator and denominator contains some positive integral powers of x with constant coefficients.
**Example 11.38**

Evaluate: ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx

**Solution**

∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

=∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

=∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

=∫f'(x)[f(x)]∫{{< katex >}} ^{dx} {{< /katex >}}dx = {{< katex >}} \frac{[f(x)]^{n+1}}{dx} {{< /katex >}}


=tanx+(-cotx)+c

=tanx-cotx+c

Integrals of the form 
 ∫ {{< katex >}} \frac{dx}{ax^{2}+bx+c} {{< /katex >}} and ∫{{< katex >}} \frac{dx}{\sqrt{ax^{2}+bx+c}} {{< /katex >}}

First we express ax{{< katex >}}^{2}{{< /katex >}}+bx+c as sum or difference of two square terms that is, any one of the
forms to Type I. The following rule is used to express the expression ax{{< katex >}}^{2}{{< /katex >}}+bx+c  as a sum or 
difference of two square terms.

(1) Make the coefficient of x{{< katex >}}^{2}{{< /katex >}} as unity.
(2) Completing the square by adding and subtracting the square of half of the coefficient of x.

**Example 11.39**

Integrate the following with respect to x:

(i) (1-x{{< katex >}}^{3} {{< /katex >}}){{< katex >}} ^{2} {{< /katex >}}           (ii){{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}}

**Solution**

(i) ∫(1-x{{< katex >}}^{3} {{< /katex >}}){{< katex >}} ^{2} {{< /katex >}}  dx = ∫(1-2x{{< katex >}} ^{2} {{< /katex >}} + x{{< katex >}} ^{6} {{< /katex >}} )dx

= ∫dx-2∫x{{< katex >}} ^{3} {{< /katex >}} dx +∫x{{< katex >}} ^{6} {{< /katex >}} dx

=x{{< katex >}} \frac{x^{4}}{2} {{< /katex >}}+{{< katex >}} \frac{x^{7}}{7} {{< /katex >}}+c

(ii)         ∫{{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}} dx = ∫({{< katex >}} \frac{x^{2}}{x^{3}} {{< /katex >}}-{{< katex >}} \frac{x}{x^{3}} {{< /katex >}}+{{< katex >}} \frac{1}{x^3} {{< /katex >}})dx          

=∫{{< katex >}} \frac{1}{x} {{< /katex >}}dx -∫{{< katex >}} \frac{1}{x^{x}} {{< /katex >}}dx+∫{{< katex >}} \frac{1}{x^{3}} {{< /katex >}}dx. 

∫{{< katex >}} \frac{x^{2}-x+1}{x^{3}} {{< /katex >}}dx =log|x|+{{< katex >}} \frac{1}{x} {{< /katex >}}-{{< katex >}} \frac{1}{2x^{2}} {{< /katex >}}+c

**EXERCISE 11.10**

 Integrate the following with respect to x

 (1) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (2) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3)

**Example 11.40**

Evaluate the following with respect to x:

 (i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx (ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx (iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx

 **Solution**

(i)∫(4x+5){{< katex >}}^{6}{{< /katex >}} dx = {{< katex >}} \frac{1}{4} {{< /katex >}} {{< katex >}} \frac{4x+5}{6+1} {{< /katex >}} = {{< katex >}} \frac{(4x+5)}{28} {{< /katex >}}+c

(ii)∫{{< katex >}}\sqrt{15-2x}{{< /katex >}}dx = ∫(15-2x){{< katex >}}^{1/2}{{< /katex >}} dx 

(iii)∫{{< katex >}} \frac{1}{((3x+7))} {{< /katex >}}dx = ∫(3x+7){{< katex >}}^{-4}{{< /katex >}}

**EXERCISE 11.11**

 Integrate the following with respect to x

 (1) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (2) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3)

**Example 11.41**

Integrate the following with respect to x

 (i) 2/cos x    (ii) cotx/sinx    (iii) sinx /cosx    (iv) {{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}}

 **solution**

(i) ∫{{< katex >}} \frac{1}{cosx} {{< /katex >}} = ∫ secx xdx= tanx+c 

(ii) ∫{{< katex >}} \frac{cotx}{sinx} {{< /katex >}}dx = ∫cosecxcotx dx = -cosecx+c

(iii)∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}dx= ∫{{< katex >}} \frac{sinx}{cosx} {{< /katex >}}.{{< katex >}} \frac{1}{cosx} {{< /katex >}}dx = ∫tanxsecx dx = secx +c

(iv) ∫{{< katex >}} \frac{1}{\sqrt[]{}1+x} {{< /katex >}} dx = sinx+c

**EXERCISE 11.12**

 Integrate the following with respect to x

 (1) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (2) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (3) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3)

**EXERCISE 11.13**

 Integrate the following with respect to x
  (1) (i) 12{{< katex >}}^{3}{{< /katex >}} (ii) x{{< katex >}}^{23}{{< /katex >}}/x{{< katex >}}^{25}{{< /katex >}}
     (iii) e{{< katex >}}^{x}{{< /katex >}}
     
(2) (i) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}} (ii) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}}

(3) (X+4){{< katex >}}^{5} {{< /katex >}}+{{< katex >}} \frac{5}{(2-5X){^{4}}} {{< /katex >}} -cosec{{< katex >}} ^{(3x-1)} {{< /katex >}}   

  (4) 4cos(5-2x)+9e{{< katex >}} ^{3x-6} {{< /katex >}}+{{< katex >}} \frac{24}{6-4x} {{< /katex >}}          

  (5) sec{{< katex >}}^{2} {{< /katex >}}{{< katex >}} \frac{x}{5} {{< /katex >}} + 18cos2x+10sec(5x+3)tan(5x+3)

(6) (i) 12{{< katex >}}^{3}{{< /katex >}} (ii) x{{< katex >}}^{23}{{< /katex >}}/x{{< katex >}}^{25}{{< /katex >}}
     (iii) e{{< katex >}}^{x}{{< /katex >}}
     
(7) (i) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}} (ii) (1+x{{< katex >}}^{2}{{< /katex >}}){{< katex >}}^{-1}{{< /katex >}}


(8) (i) 1/x{{< katex >}}^{-e}{{< /katex >}}      (ii) x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}}     (iii) 1/x{{< katex >}}^{3}{{< /katex >}}    (iv)   {{< katex >}} \frac{1}{1+x} {{< /katex >}}

(9)1/x{{< katex >}}^{-e}{{< /katex >}} 

   (i) ∫1/e{{< katex >}}^{-x}{{< /katex >}}   

   (ii) ∫x{{< katex >}}^{2}{{< /katex >}}/x{{< katex >}}^{3}{{< /katex >}} (dx) =∫ {{< katex >}} \frac{1}{x} {{< /katex >}} dx = log|x|+c

   (iii) ∫1/x{{< katex >}}^{3}{{< /katex >}}dx = ∫x{{< katex >}}^{-3}{{< /katex >}} dx =  {{< katex >}} \frac{x}{-3+1} {{< /katex >}}+c=  {{< katex >}} \frac{1}{2x} {{< /katex >}}+c

   (iv)  ∫{{< katex >}} \frac{1}{1+x} {{< /katex >}} dx = tan{{< katex >}}^{-1}{{< /katex >}}x+c

(10){{< katex >}} \frac{1}{3x-2} {{< /katex >}}

(i) e{{< katex >}}^{3x}{{< /katex >}}     (ii) e{{< katex >}}^{5-4x}{{< /katex >}}      (iii){{< katex >}} \frac{1}{3x-2} {{< /katex >}} 

(11)∫{{< katex >}} \frac{1}{3x-2} {{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}

(i) ∫e{{< katex >}}^{3x}{{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}  e{{< katex >}}^{3x}{{< /katex >}}+c

(ii) ∫e{{< katex >}}^{5-4x}{{< /katex >}} dx =  (-e{{< katex >}}^{5-4x}{{< /katex >}}/4) +c

(iii) ∫{{< katex >}} \frac{1}{3x-2} {{< /katex >}} dx = {{< katex >}} \frac{1}{3} {{< /katex >}}log|(3x-2)|+c

(11)∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

(i)∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

(ii){{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c



(12) ∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx


(i)∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx = ∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

(ii)∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

(iii)∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx

(13) ∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx

(i)∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx = ∫2sin{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}dx =∫tan{{< katex >}} ^{2} {{< /katex >}}dx

(ii)∫(sec{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}-1)dx = {{< katex >}} \frac{tan{\frac{x}{2}}}{\frac{1}{2}} {{< /katex >}}-x+c

(iii)2tan{{< katex >}} \frac{x}{2} {{< /katex >}}-x+c.

(14) ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx

(i)∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx = ∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

(ii)∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

(iii)sinx-cosx+c

(15)∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx

(i)∫{{< katex >}}\sqrt{1+cos2x}{{< /katex >}}dx 

(ii)∫{{< katex >}}\sqrt{2cos^{2}x}{{< /katex >}} dx

(iii){{< katex >}}\sqrt{2}{{< /katex >}}∫cosxdx = {{< katex >}}\sqrt{2}{{< /katex >}}sinx+c


(15)∫(tanx+cotx){{< katex >}}^{2}{{< /katex >}}dx


(i)∫[tan{{< katex >}}^{2}{{< /katex >}}x+2tanxcotx+cot{{< katex >}}^{2}{{< /katex >}}x]dx

(ii)∫[(sec{{< katex >}}^{2}{{< /katex >}}x-1)+2+(cosec{{< katex >}}^{2}{{< /katex >}}x-1)]dx

(iii)∫(sec{{< katex >}}^{2}{{< /katex >}}x+cosec{{< katex >}}^{2}{{< /katex >}}x)dx


(16)∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx


(1)∫{{< katex >}} \frac{1-cosx}{1+cosx} {{< /katex >}}dx = ∫2sin{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}dx =∫tan{{< katex >}} ^{2} {{< /katex >}}dx

(2)∫(sec{{< katex >}} ^{2} {{< /katex >}}{{< katex >}} \frac{x}{2} {{< /katex >}}-1)dx = {{< katex >}} \frac{tan{\frac{x}{2}}}{\frac{1}{2}} {{< /katex >}}-x+c

(3)2tan{{< katex >}} \frac{x}{2} {{< /katex >}}-x+c.

(17) ∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx


(1)∫{{< katex >}}\sqrt{1+sin2x}{{< /katex >}}dx 

(2)∫{{< katex >}}\sqrt{(cos^{2}x+sin^{2}x)+(2sinxcosx)}{{< /katex >}}dx

(3)∫{{< katex >}}\sqrt{(cosx+sinx)^{2}}{{< /katex >}}dx = ∫(cosx+sinx)dx

(4)sinx-cosx+c
