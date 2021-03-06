# Q1. Why is it useful to transform an nth-order ODE into n 1st-order ODEs?
- A. It's the only way to know how many state variables are involved.
- B. To see if it's linear.
- C. Because that's the form in which ODE solvers want them.
- D. Because it's fun.
- Answer: 

# Q2. If you transformed this ODE into a set of 1st-order ODEs, how many "helper variables" would you need?
<a href="http://www.codecogs.com/eqnedit.php?latex=x'''&space;&plus;&space;x'&space;-&space;3&space;sinx&space;=&space;0" target="_blank"><img src="http://latex.codecogs.com/gif.latex?x'''&space;&plus;&space;x'&space;-&space;3&space;sinx&space;=&space;0" title="x''' + x' - 3 sinx = 0" /></a>
- A. None.
- B. This transformation isn't possible for this ODE.
- C. One
- D. Two
- E. Three

# Q3. What is the state vector of the simple harmonic oscillator (SHO)?
- A. <a href="http://www.codecogs.com/eqnedit.php?latex=[x,v]" target="_blank"><img src="http://latex.codecogs.com/gif.latex?[x,v]" title="[x,v]" /></a>
- B. <a href="http://www.codecogs.com/eqnedit.php?latex=[x,v]^T" target="_blank"><img src="http://latex.codecogs.com/gif.latex?[x,v]^T" title="[x,v]^T" /></a>
- C. <a href="http://www.codecogs.com/eqnedit.php?latex=[\theta,\omega]" target="_blank"><img src="http://latex.codecogs.com/gif.latex?[\theta,\omega]" title="[\theta,\omega]" /></a>
- Answer: 

# Q4. The SHO equations are below:
<a href="http://www.codecogs.com/eqnedit.php?latex=x'=v,&space;v'=-x" target="_blank"><img src="http://latex.codecogs.com/gif.latex?x'=v,&space;v'=-x" title="x'=v, v'=-x" /></a>
 If x=1 and v=1, what are x' and v'?
 
# Q5. Refer to to the SHO equations in question 4.  
If x=0 and v=1, what are x' and v'?
A. x'=0 and v'=1
B. x'=1 and v'=0
C. x'=0 and v'=0
D. None of the above

# Q6. The state-space point x=0, v=0 is a fixed point of the SHO dynamics.

# Q7. The state-space point x=1, v=0 is a fixed point of the SHO dynamics.
# Q8. Difference equations and differential equations can both involve multiple state variables.
# Q9. Difference equations and differential equations both involve derivatives.
# Q10. A difference equation gives you the next state of the system,whereas a differential equation gives you the direction in which the state evolves.
# Q11. This picture shows a trajectory of the undamped SHO system, starting from [1,1] with a step size of 0.1.  Which solver was used to generate it?
# Q12. What will happen to the solutions generated by forward and backward Euler methods as you change the time step? (experts: neglect the effects of floating-point arithmetic when you're answering this question.)  
- Solutions produced by both methods will improve (i.e., get more accurate) as you decrease the time step.
- Solutions produced by both methods will improve (i.e., get more accurate) as you increase the time step.
- There will be no change in accuracy in either method as you decrease the time step.

# Q13. Comparing the amount of work done by a computer that is running the forward Euler algorithm to generate a one-second-long trajectory of the SHO system using two different time steps: 0.1 and 0.2 seconds. (Experts: only consider main loop iteration costs, not startup, and neglect all floating-point effects.)
- A. Both trajectories will require about the same amount of computational effort.
- B. The trajectory with the longer time step will require about twice as much work.
- C. The trajectory with the shorter time step will require about twice as much work.
- D. The trajectory with the shorter time step will require more than twice as much work.
- E. The trajectory with the longer time step will require more than twice as much work.

# Q14. Use your forward Euler solver from HW 5.4 on the SHO equations with k=2, m=1, and \beta=0, from the initial condition x(t=0)=-1 , v(t=0)=-2, with a timestep of 0.05, to compute the values of x and v at t=0.5.  [Note: this is problem 1 on HW 5.4 with a different m and a different h]
- x(t=0.5)\approx -1.528,\,\, v(t=0.5) \approx 0.625
- x(t=0.5)\approx -1.7209,\,\, v(t=0.5) \approx -0.6198
- x(t=0.5)\approx -1.7621 ,\,\, v(t=0.5) \approx -0.6439
