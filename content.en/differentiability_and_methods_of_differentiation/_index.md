---
title: 'Differentiability and Methods of Differentiation'
weight: 10
---

# Content Will be Added Soon

In this chapter we discuss the concept of derivative and related concepts and develop tools  necessary for solving real life problems. In this connection, let us look at the following problem of 
finding average velocity. Almost everyone has an intuitive notion of speed or velocity as a rate at which a distance is 
covered in a certain length of time. When, say, a bus travels 60 km in one hour, the average velocity 
of the bus must have been 60 km/h. Of course, it is difficult to maintain this rate of 60 km/h for the 
entire trip because the bus slows down for towns and speeds up when it passes cars. In other words, 
the velocity changes with time. If a bus company’s schedule demands that the bus travel 60 km from 
one town to another in one hour, the driver knows instinctively that he must compensate for velocities 
or speeds greater than this at other points in the journey. Knowing that the average velocity is 60 km/h 
does not, however, answer the question: What is the velocity of the bus at a particular instant? 
In general, this average 
velocity or average speed of a 
moving object is the time rate 
of change of position defined 
by 
{{<katex display>}}v_ave=\frac{distance travelled}{time of travel}{{</katex>}}

 Consider a runner who 
 finishes a 10 km race in an 
  elapsed time of 1 h 15 min 
(1.25 h). The runner’s average 
        velocity or average speed for
        this race is:
{{<katex display>}}v_ave=\frac{10}{1.25}=8{{</katex>}}
But suppose we now wish 
to determine the runner’s exact 
velocity v at the instant the runner is one-half into the race. If the distance run in the time interval from 0 h to 0.5 h is measured to be 5 km, then
{{<katex display>}}v_ave=\frac{5}{0.5}=10{{</katex>}}
Usain Bolt’s average speed
{{<katex display>}}\frac{\Delta y}{\Delta x}=\frac{100}{9.85}=10.4{{</katex>}}
Again this number is not a measure or necessarily such a good indicator, of the instantaneous 
rate v at which the runner is moving 0.5 h into the race. If we determine that rate at 0.6 h the runner is 5.7 km from the starting line, then the average velocity from 0 h to 0.6 h is 
{{<katex>}}v_ave=\frac{5.75-5}{0.6-0.5}=7km/h{{</katex>}} The latter number is a more realistic measure of the rate v. By “shrinking” 
the time interval between 0.5 h and the time that corresponds to a measured 
position close to 5 km, we expect to obtain even better approximations to the 
runner’s velocity at time 0.5 h.
This problem of finding velocities leads us to deal with the general 
problem of finding the derivative of a general mathematical model represented by the analytic 
equation, y fx = ( ) Consequently, we will move towards in achieving the following objectives and 
subsequently deal with the analysis of derivatives

Learning Objectives
On completion of this chapter, the students are expected to
• acquire the concept of a derivative as limit of quotients.
• visualise the concept of derivative geometrically.
• understand derivative as a process of measuring changes.
• realise derivative as a tool to measure slopes of tangents to curves / rates of changes.
• understand different methods of differentiation.
• apply calculus as a tool to solve everyday real life problems

For a general curve, however, the problem is more difficult, 
for example, how would you define the tangent lines shown in the 
following figures 10.2 to 10.4.
You might say that a line is tangent to a curve at a point P if 
it touches, but does not cross, the curve at point P. This definition 
would work for the first curve (Fig. 10.2), but not for the second 
(Fig. 10.3). Or you might say that a line is tangent to a curve if 
the line touches or intersects the curve exactly at one point. This 
definition would work for a circle but not for more general curves,Essentially, the problem of finding the tangent line at a point P boils down to the problem of 
finding the slope of the tangent line at point P. You can approximate this slope using a secant line 
through the point of tangency and a second point on the curve as in the following
Essentially, the problem of finding the tangent line at a point P boils down to the problem of 
finding the slope of the tangent line at point P. You can approximate this slope using a secant line 
through the point of tangency and a second point on the curve as in the following Fig. 10.5
Let P({{<katex>}}x_0,f(x_0))be the point of tangency and Q(x_0)+{\Delta x},f(x_0)+{\Delta x_0}{{</katex>}} be the second point.
The slope of the secant line through the two points is given by substitution into the slope formula,
{{<katex>}}m=\frac{y_2-y_1}{x_2-x_1}{{</katex>}}
{{<katex>}}m_sec=\frac{fx_0+{\Delta x}-f(x_0)}{x_0+{\Delta x}-x_0}=\frac{change in y}{change in x}=\frac{{\Delta y}}{{\Delta x}}{{</katex>}} that is,
{{<katex>}}m_sec=\frac{x_0+{\Delta x}-f(x_0)}{{\Delta x}}{{</katex>}}
The right hand side of this equation is a difference quotient. The denominator Dx is the change 
in x (increment in x), and the numerator Dy = f(x0+ Dx) - f(x0) is the change in y.
The beauty of this procedure is that you can obtain more and more accurate approximations of 
the slope of the tangent line by choosing points closer and closer to the point of tangency
