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

**Example 11.10**

If f'(x)=3x{{< katex >}}^{2}{{< /katex >}}-4x+5 and f(1)=3, then find f(x) .

**Solution**

Given that   
 f'(x)=x{{< katex >}}\frac{d}{dx}{{< /katex >}}= 3x{{< katex >}}^{2}{{< /katex >}}-4x+5        

Integrating on both sides with respect to x, we get   

 ∫f'(x)dx = ∫(3x{{< katex >}}^{2}{{< /katex >}}-4x+5)dx         
 f(x)=x{{< katex >}}^{3}{{< /katex >}}-2x{{< katex >}}^{2}{{< /katex >}}+5x+c        

To determine the constant of integration c, we have to apply the given information        

f(1)=3 => 3(1){{< katex >}}^{3}{{< /katex >}}+5(1)+c=-1
thus         f(x)=x{{< katex >}}^{3}{{< /katex >}}-2x{{< katex >}}^{2}{{< /katex >}}+5x

**Example 11.11**

A train started from Madurai Junction towards Coimbatore at 3pm (time t = 0) with velocity
v(t)= 20t+50 kilometre per hour, where t is measured in hours. Find the distance covered by
the train at 5pm.

**Solution**

In calculus terminology, velocity v={{< katex >}} \frac{ds}{dt} {{< /katex >}}  is rate of change of position with time, where s is
the distance.The velocity of the train is given by

 v(t)=20t+50 

 Therefore, {{< katex >}} \frac{ds}{dt} {{< /katex >}}=20t+50 

To find the distance function s one has to integrate the derivative function.

 That is, s =∫(20t+50)dt
 s =10t{{< katex >}}^{2} {{< /katex >}}+50t+c

The distance covered by the train is zero when time is zero. Let us use this initial condition
s=0 at t=0 to determine the value c of the constant of integration.

 ⇒s= 10t{{< katex >}}^{2} {{< /katex >}}+50t+c     ⇒c=0

Therefore,   s=10t{{< katex >}}^{2} {{< /katex >}}+50t
The distance covered by the train in 2 hours (5pm-3pm) is given by substituting
t = 2 in the above equation, we get
 
 s = 10(2){{< katex >}}^{2} {{< /katex >}}+50(2)=140km.

**Example 11.12**

The rate of change of weight of person w in kg with respect to their height h in centimetres is
given approximately by {{< katex >}}\frac{dw}{dh} {{< /katex >}} = 4.364*10{{< katex >}}^{-5} {{< /katex >}} h{{< katex >}}^{2} {{< /katex >}}. Find weight as a function of height. Also find the
weight of a person whose height is 150 cm.

**Solution**

The rate of change of weight with respect to height is

{{< katex >}}\frac{dw}{dh} {{< /katex >}}=4.364*10{{< katex >}}^{-5} {{< /katex >}} h{{< katex >}}^{2} {{< /katex >}}      
w=∫4.364*10{{< katex >}}^{-5} {{< /katex >}} h{{< katex >}}^{2} {{< /katex >}}  dh      
w=4.364*10{{< katex >}}^{-5} ({{< /katex >}} h{{< katex >}}^{3} {{< /katex >}}/3)+c

One can obviously understand that the weight of a person is zero when height is zero.
Let us find the value c of the constant of integration by substituting the initial condition w = 0,
at h = 0 , in the above equation            
w=4.364*10{{< katex >}}^{-5} ({{< /katex >}} h{{< katex >}}^{3} {{< /katex >}}/3)+c => c=0

The required relation between weight and height of a person is

w=4.364*10{{< katex >}}^{-5} ({{< /katex >}} h{{< katex >}}^{3} {{< /katex >}}/3)

When the height h = 150cm, 

w=4.364*10{{< katex >}}^{-5} ({{< /katex >}} 150{{< katex >}}^{3} {{< /katex >}}/3)

When the height h = 150cm, the weight isw kg = 49 (approximately)
Therefore, the weight of the person whose height 150cm is 49 kg.

**Example 11.13**

A tree is growing so that, after t - years its height is increasing at a rate of 18/{{< katex >}}\sqrt{t}{{< /katex >}}cm per year.           
Assume that when t = 0, the height is 5 cm.                 
(i) Find the height of the tree after 4 years.
(ii) After how many years will the height be 149 cm?

**Solution**

The rate of change of height h with respect to time t is the derivative of h with respect to t.      
 Therefore, {{< katex >}} \frac{dh}{dt} {{< /katex >}} =  18/{{< katex >}}\sqrt{t}{{< /katex >}} = 18t{{< katex >}}^{-1/2}{{< /katex >}}
 
 So, to get a general expression for the height, integrating the above equation with
respect to t.    
 h=18t{{< katex >}}^{-1/2}{{< /katex >}}dt = 18(2t{{< katex >}}^{1/2}{{< /katex >}})+c = 36{{< katex >}}\sqrt{t}{{< /katex >}}+c          
Given that when t=0, the height h= 5cm.              
5=0+c => c=5                    
h=36{{< katex >}}\sqrt{t}{{< /katex >}}+5            

(i) To find the height of the tree after 4 years.                
 When t = 4 years,        
 h=36{{< katex >}}\sqrt{t}{{< /katex >}}+5 =>h=36{{< katex >}}\sqrt{4}{{< /katex >}}+5 =77

 The height of the tree after 4 years is 77 cm            
(ii) When h = 149cm
h=36{{< katex >}}\sqrt{t}{{< /katex >}}+5 =>149 =36{{< katex >}}\sqrt{t}{{< /katex >}}+5         
{{< katex >}}\sqrt{t}{{< /katex >}}= {{< katex >}} \frac{149-5}{36} {{< /katex >}}=4 =>t =16

 Thus after 16 years the height of the tree will be 149 cm.

**Example 11.14**

At a particular moment, a student needs to stop his speedy
bike to avoid a collision with the barrier ahead at a distance
40 metres away from him. Immediately he slows (retardation)
the bike under braking at a rate of 8 metre/second{{< katex >}}^{2}{{< /katex >}} . If the bike
is moving at a speed of 24m/s, when the brakes are applied,
would it stop before collision?

**Solution**

Let a be the acceleration, v be the velocity of the car, and s be the distance.

Stated in calculus terminology, velocity, v ={{< katex >}} \frac{ds}{dt} {{< /katex >}}, is the rate of change of position with time,
and acceleration, a={{< katex >}} \frac{ds}{dt} {{< /katex >}}, is rate of change of velocity with time.         
 The acceleration to be negative because if you take the direction of movement to be positive,
then for a bike that is slowing down, its acceleration vector will be oriented in the opposite
direction of its motion (retardation).
Given that the retardation of the car is 8 meter/second{{< katex >}}^{2} {{< /katex >}} .          
 Therefore, a = {{< katex >}} \frac{dv}{dt} {{< /katex >}} = -8 meter/second{{< katex >}}^{2} {{< /katex >}}      

 Therefore, v= ∫ a dt = ∫-8dt = -8t+c{{< katex >}}_{1} {{< /katex >}}

When the brakes are applied,           
 t = 0, and v = 24m/s.            
 So, 24= -8(0)+c∫ => c{{< katex >}}_{2} {{< /katex >}} = 24        
 Therefore, v =-8t+24.               
 That is, {{< katex >}}\frac{ds}{dt}{{< /katex >}} =-8t+24
It is required to find the distance, not the velocity, so need more integration in order.
 s = ∫v dt= ∫f(-8t+24)dt        
 s =-4t{{< katex >}}^{2} {{< /katex >}}+24t+c{{< katex >}}_{2} {{< /katex >}}                

To determine c{{< katex >}}_{2} {{< /katex >}} , the stopping distance s is measured from where, and when, the brakes are
applied so that at t = 0,s =  0 .
 s = -4t{{< katex >}}^{2} {{< /katex >}}+24t+c{{< katex >}}_{2} {{< /katex >}}  =>0=-4(0){{<katex>}}^{2}{{</katex>}}+24(0)+c{{<katex>}}_{2}{{</katex>}} => c{{<katex>}}_{2}{{</katex>}}=0
s =-4t{{<katex>}}^{2}{{</katex>}}+24t           

The stopping distance s could be evaluated if we knew the braking time. The time can be
determined from the speed statement.
The bike stops when v = 0 , ⇒ v= -8t + 24 ⇒0 =−8t + 24 ⇒ t = 3.
When t = 3 , we get
 s = -4t{{<katex>}}^{2}{{</katex>}}+24t =>s=-4(3){{<katex>}}^{2}{{</katex>}}+24(3)     
 s = 36 metres < 40 metres        
 The bike stops at a distance 4 metres to the barrier.

**EXERCISE 11.4**

(1) If f'(x)=4x-5 and f(2)=1, find f(x). 

(2) Iff'(x)=9x{{<katex>}}^{2}{{</katex>}}-6x and f(0)=-3, find f(x). 

(3) If f"(x)=12x-6 and f(1)=30, f'(1)=5 find f(x).         

(4) A ball is thrown vertically upward from the ground with an initial velocity of 39.2 m/sec. If
the only force considered is that attributed to the acceleration due to gravity, find
(i) how long will it take for the ball to strike the ground?
(ii) the speed with which will it strike the ground? and
(iii) how high the ball will rise?

(5) A wound is healing in such a way that t days since Sunday the area of the wound has been
decreasing at a rate of -6/(t+2){{<katex>}}^{2}{{</katex>}} cm{{<katex>}}^{2}{{</katex>}} per day where 0<t≤8. If on Monday the area of the wound was 1.4 cm{{<katex>}}^{2}{{</katex>}}         
  (i) What was the area of the wound on Sunday?              
 (ii) What is the anticipated area of the wound on Thursday if it continues to heal at the same
rate?