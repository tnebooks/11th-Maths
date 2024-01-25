---
title: 'Methods of Integration'
weight: 7
---

# 7  Methods of Integration

Integration is not as easy as differentiation. This is first due to its nature. Finding a derivative of
a given function is facilitated by the fact that the differentiation itself has a constructive character. A

Suppose we are asked to find the derivative of log x, we know in all details how to proceed in order
to obtain the result.
When we are asked to find the integral of log x, we have no constructive method to find integral or
even how to start.
In the case of differentiation we use the laws of differentiation of several functions in order to find
derivatives of their various combinations, like their sum, product, quotient, composition of functions etc.
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

11.7.1 Decomposition method
Sometimes it is very difficult to integrate the given function directly. But it can be integrated after
decomposing it into a sum or difference of number of functions whose integrals are already known.
 For example ( )2 3 1 , − x
2
3
x x 1
x
− + , cos5 sin 3 x x , 3 cos , x
2 1 x
x
e
e
− , do not have direct formulae
to integrate. But these functions can be decomposed into a sum or difference of functions, whose
individual integrals are known. In most of the cases the given integrand will be any one of the
algebraic, trigonometric or exponential forms, and sometimes combinations of these functions.

11.7.3 Method of substitution or change of variable
	 The method of substitution in integration is similar to finding the derivative of function of
function in differentiation. By using a suitable substitution, the variable of integration is changed to
new variable of integration which will be integrated in an easy manner.
	 We know that, if u is a function of x then . du
u
dx = ′
Hence we can write f u u dx f u du () () ′ = ∫ ∫
	 Thus, f g x g x dx f u du u g x [ ( )] ( ) ( ) , where ( ) ′ = = ∫ ∫
	 The success of the above method depends on the selection of suitable substitution
either x = f(u) or u = g(x).
Note 11.2
The substitution for the variable of integration is in trigonometric function, use a rough
diagram to find the re -substitution value for it. Suppose the variable of integration x is substituted
as x = tanθ . After integration suppose the solution is sec cosec θ θ +
For example, if x  tan ,  then from 

11.7.5 Integration by parts
Integration by parts method is generally used to find the integral when the integrand is a product
of two different types of functions or a single logarithmic function or a single inverse trigonometric
function or a function which is not integrable directly. From the formula for derivative of product of
two functions we obtain this useful method of integration.
If u and v are two differentiable functions then we have
 d u( ) v v   du udv
 udv   d u( ) v vdu
 Integrating
 udv d uv vdu      ( )
 udv uv vdu    
udv ∫ in terms of another integral vdu ∫ and does not give a final expression for the integral
udv ∫ . It only partially solves the problem of integrating the product u dv . Hence the term ‘Partial
Integration’ has been used in many European countries. The term “Integration by Parts” is used in
many other countries as well as in our own.
The success of this method depends on the proper choice of u
(i) If integrand contains any non integrable functions directly from the formula, like logx,
tan−1
x etc., we have to take these non integrable functions as u and other as dv.
(ii) If the integrand contains both the integrable function, and one of these is xn
 (where n is a
positive integer) then take u = xn
.
(iii) For other cases the choice of u is ours.

11.7.6 Bernoulli’s formula for Integration by Parts
If u and v are functions of x, then the Bernoulli’s rule is
1 2 udv uv u v u v =− + − ′ ′′ ∫ 
where uu u ′ ′′ ′′′ , , ,... are successive derivatives of u and
v v, ,v v, , 1 2 3  are successive integrals of dv
Bernoulli’s formula is advantageously applied when n u x = ( n is a positive integer)
For the following problems we have to apply the integration by parts two or more times to find the
solution. In this case Bernoulli’s formula helps to find the solution easily.

11.7.8 Integrals of the form (i) sin ax e bx dx ∫ (ii) ∫ cos ax e bx dx
The following examples illustrate that there are some integrals whose integration continues
forever. Whenever we integrate function of the form cos or sin , ax ax e bx e bx we have to apply the
Integration by Parts rule twice to get the similar integral on both sides to solve.