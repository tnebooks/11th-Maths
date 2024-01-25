---
title: 'Simple applications'
weight: 6
---

# 6 Simple applications

So far in this section we have been using x as the variable of integration. In the case of applications,
it is often convenient to use a different variable. For instance in the equation of motion the independent
variable is time and the variable of integration is t.
In this section we discuss how integration is used to find the position and velocity of an object,
given its acceleration and similar types of problems. Mathematically, this means that, starting with
the derivative of a function, we must find the original function. Many common word which indicate
derivative such as rate, growth, decay, marginal, change, varies, increase, decrease etc. 
Example 11.10
If 2 fx x x f ′( ) 3 4 5 and (1) 3, = −+ = then find f x( ) .
Solution
Given that ( ) 2 () () 3 4 5 d f x fx x x dx ′ = = −+
Integrating on both sides with respect to x, we get
      f x( ) dx ( ) 3 4 x x 5 dx 2
 3 2 fx x x x c () 2 5 =− ++
To determine the constant of integration c, we have to apply the given information f (1) 3 =
 3 2 f (1) 3 3 (1) 2(1) 5(1) 1 = ⇒ = − + + ⇒ =− c c
 Thus 3 2 fx x x x () 2 5 1 =− +− .
Example 11.11
A train started from Madurai Junction towards Coimbatore at 3pm (time t = 0) with velocity
vt t ( ) 20 50 = + kilometre per hour, where t is measured in hours. Find the distance covered by
the train at 5pm.
Solution
In calculus terminology, velocity =
ds
v
dt is rate of change of position with time, where s is
the distance.The velocity of the train is given by
 vt t ( ) 20 50 
 Therefore, 20 50 ds
t
dt
= +
To find the distance function s one has to integrate the derivative function.
 That is, s t dt = + ( ) 20 50 ∫
 2 s t tc = ++ 10 50
The distance covered by the train is zero when time is zero. Let us use this initial condition
s t = = 0 at 0 to determine the value c of the constant of integration.
 2 ⇒= + + ⇒= s t tc c 10 50 0
Therefore, 2 st t = + 10 50
The distance covered by the train in 2 hours (5pm-3pm) is given by substituting
t = 2 in the above equation, we get
 2
s = += 10(2) 50(2) 140 km.
Example 11.12
The rate of change of weight of person w in kg with respect to their height h in centimetres is
given approximately by 5 2 4.364 10 dw h
dh
− = × . Find weight as a function of height. Also find the
weight of a person whose height is 150 cm.
Solution
The rate of change of weight with respect to height is
w −   = ×  
When the height h = 150cm, the weight isw kg = 49 (approximately)
Therefore, the weight of the person whose height 150cm is 49 kg.
Example 11.13
A tree is growing so that, after t - years its height is increasing at a rate of 18
t
cm per year.
Assume that when t = 0, the height is 5 cm.
(i) Find the height of the tree after 4 years.
(ii) After how many years will the height be 149 cm?
Solution
The rate of change of height h with respect to time t is the derivative of h with respect to t.
 Therefore, dh
dt = 18 18
1
2
t
 t

 So, to get a general expression for the height, integrating the above equation with
respect to t.
 h = 18 18 2
1
2
1
2 t dt t c 
   ( )   36 t c
Given that when t = 0, the height h = 5 cm.
 5 = 0 5  c c 
 h = 36 5 t + .
(i) To find the height of the tree after 4 years.
 When t = 4 years,
 h = 36 t h  5 3   6 4 5 7  7
 The height of the tree after 4 years is 77 cm
(ii) When h = 149cm
 h = 36 5 149 36 5 t t    
 t = 149 5
36
4 16    t 
 Thus after 16 years the height of the tree will be 149 cm.
Example 11.14
At a particular moment, a student needs to stop his speedy
bike to avoid a collision with the barrier ahead at a distance
40 metres away from him. Immediately he slows (retardation)
the bike under braking at a rate of 2 8 metre/second . If the bike
is moving at a speed of 24m/s, when the brakes are applied,
would it stop before collision?
Solution
Let a be the acceleration, v be the velocity of the car, and s be the distance.

Stated in calculus terminology, velocity, =
ds
v
dt , is the rate of change of position with time,
and acceleration, dv
a
dt = , is rate of change of velocity with time.
 The acceleration to be negative because if you take the direction of movement to be positive,
then for a bike that is slowing down, its acceleration vector will be oriented in the opposite
direction of its motion (retardation).
Given that the retardation of the car is 2 8 meter/second .
 Therefore, a = dv
dt  8 2 meter/second .
 Therefore, v = a dt d   t t    c  8 8 1
 v =   8 1 t c .
When the brakes are applied,
 t = 0, and v = 24m/s.
 So, 24 =   8 0   24 1 1 ( ) c c
 Therefore, v =   8 2 t 4.
 That is, ds
dt =   8 2 t 4.
It is required to find the distance, not the velocity, so need more integration in order.
 s = v dt t    dt  ( ) 8 24
 s =   4 24  2
2 t t c
To determine 2 c , the stopping distance s is measured from where, and when, the brakes are
applied so that at t s = = 0, 0 .
 s =   4 24 0     4 0   24 0 0   2
2
2
2 2 t t c c () () c
 s =   4 24 2
t t
The stopping distance s could be evaluated if we knew the braking time. The time can be
determined from the speed statement.
The bike stops when v = 0 , ⇒ =− + v t 8 24 ⇒ =− + 0 8 24 t ⇒ =t 3.
When t = 3 , we get
 s = 2 2 − + ⇒ =− + 4 24 4(3) 24(3) t ts
 s = 36 metres < 40 metres
 The bike stops at a distance 4 metres to the barrier.
EXERCISE 11.4
(1) If fx x f ′( ) 4 5 and (2) 1, = − = find f x( ).
(2) If 2 fx x x f ′( ) 9 6 and (0) 3, = − = − find f x( ).
(3) If fx x f ′′( ) 12 6 and (1) 30, =− = f ′(1) 5 = find f x( ).

(4) A ball is thrown vertically upward from the ground with an initial velocity of 39.2 m/sec. If
the only force considered is that attributed to the acceleration due to gravity, find
(i) how long will it take for the ball to strike the ground?
(ii) the speed with which will it strike the ground? and
(iii) how high the ball will rise?
(5) A wound is healing in such a way that t days since Sunday the area of the wound has been
decreasing at a rate of 2
6
( 2) t − +
cm2
per day where 0<t≤8. If on Monday the area of the
wound was 1.4 cm2
(i) What was the area of the wound on Sunday?
 (ii) What is the anticipated area of the wound on Thursday if it continues to heal at the same
rate?