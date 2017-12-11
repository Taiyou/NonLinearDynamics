# Q1. Numerical dynamics—the extra effects added to the true trajectory of a dynamical system by the ODE solver that you use to generate that trajectory—are affected by the time step.
Answer:

# Q2. Numerical dynamics, as defined above, are affected by the solver method (e.g., whether you use forward or backward Euler).

# Q3. Numerical dynamics (as defined above) are obvious and easy to spot.

# Q4. The effects produced by numerical dynamics can look like real, physical effects.

# Q5. Dynamical error can "snowball" over the course of the solution of an ODE.

# Q6. Which of the following is a method to derive the mathematical form of the local (one-step) truncation error of the forward Euler method?
- By running two nearby trajectories and watching the distance between them.
- By using a Taylor series.
- By requesting divine intervention.

# Q7. What is machine epsilon?
- A way to describe the smallest positive number that a computer can store.
- A way to describe the largest positive number that a computer can store.
- The clock rate of the computer's processor.
- The name for the portion of the truncation-error term related to the stepsize, e.g.,  for forward Euler.

# Q8. Why should we care about machine epsilon?
- Because it can introduce truncation error into computations.
- Because it can introduce roundoff error into computations.
- Because it can introduce observational error into computations.

# Q9. How does the trapezoidal method for solving ODEs work, loosely speaking?
- It is an adaptive version of forward Euler.
- It averages a forward and backward Euler step to approximate each step
- It is a symplectic method.

# Q10. Why is it a good idea to adapt the time step of an ODE solver 'on the fly'?
- Because dynamical landscapes can be highly heterogeneous (different shapes in different regions).
- Because using a tiny time step in a dynamically smooth region can be overkill.
- Because using a large time step in a dynamically complex region can cause errors.
- All of the above.
- None of the above.

# Q11. Which of these strategies is a good way to adapt the time step of an ODE solver?
- Use different-size time steps and adapt the time step if the results change.
- Use a different ODE and adapt the time step if the results change.
- Generate a longer trajectory and adapt the time step if the endpoint is different.

# Q12. The trapezoidal method is a member of the RK family of ODE solvers.

# Q13. What should you do in order to increase your confidence that an ODE solver is giving you a good answer?
- Change the time step and see if that changes the results.
- Change the arithmetic precision and see if that changes the results.
- Change the method and see if that changes the results.
- All of the above.

# Q14. Can you ever prove that an ODE solver is giving you the correct answer when you apply it to a chaotic ODE system?

# Q15. The shadowing lemma tells us that small changes in the parameters of a chaotic dynamical system bump the trajectory onto a "shadow trajectory" — an attractor thread that you'd have gotten to eventually anyway (in forward or backward time).

# Q16. Use your trapezoidal solver from HW 6.3 on the SHO equations with k=2, m=0.5, and =0, from the initial condition x(t=0)=-1 , v(t=0)=-2, with a timestep of 0.05, to compute the values of x and v at t=0.5.  [Note: this is like problem 1 on HW 6.3, but with a different h]

