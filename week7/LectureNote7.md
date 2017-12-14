# 7.1 Dynamis and state-space deformation
- Attractors
  - Attractors exist only in dissipative systems!
  - Dissipation <--> contraction of state space under the influence of the dynamics.
  - it can still have chaos if no dissipation but not just chaotic attractors.
  
 ## Q1. Smale's horseshoe is a map of the unit square into itself (experts: assume that any region of the plane can be continually deformed to the unit square).
 ## Answer: True.
 ## Q2. Smale's horseshoe maps some close points far apart (& vice-versa).
 ## Answer: True.
 ## Q4. Horseshoes:
 ### (a) Only turn up in the dynamics of the Smale horseshoe map:
 ### Answer: False. not only in the smale horsehoe map
 ### (b) are important because they play a role in proofs of chaos:
 ### Answer: True
 ### (c) turn up in the dynamics of the pendulum:
 ### Answer: True
 ## Q5. Dissipation is a necessary condition for the existence of attractors.
 ### Answer: True
 
 # 7.2 Lyapunov exponents.
 - Lyapunov exponents:
  - n-dim system has n lambda $\lambda$
  - negative \lambda compress state space along stable manifolds.
  - positive \lambda stretch it along unstable manifolds
  - \sum \lambda_i < 0 for disipative systems
  - positive \lambda is a signature of chaos (not necessary and sufficient condition)
  - \lambda_i are properties of attractors: same for all ICs in one basin.
  - biggest one (\lambda_1) dominates as t -> \infty
  - |\delta_i| \prompt e^{\lambda_1 t}
  
## Q1. Sensitive dependence on initial conditions can only occur in a dynamical system that has at least one unstable manifold.
## Answer: True.

## Q2. An attractor can only exist in a dynamical system that has at least one stable manifold.
## Answer: True. negative \lambda compress state space along stable manifolds.

## Q3. Each stable manifold in a dynamical system has an associated Lyapunov exponent λ whose value is negative.
## Answer: True. 

## Q4. What's the difference between local and global λs?
### A. Local λs are only defined for non-dissipative systems
### B. Local λs reflect the behavior of trajectories on small patches of the attractor
### C. Local λs are the average stretching and shrinking across the entire attractor
## Answer: B. Local λs reflect the behavior of trajectories on small patches of the attractor.

## Q5. λs are only associated with stable manifolds.
## Answer: No. λs are associated with unstable and stable manifolds.

## Q6. There are n λs in an n-dimensional dynamical system (experts: count repeated λs individually).
## Answer: True.

## Q7. If λ1 (the largest λ) is positive then it dominates in the long term.
## Answer: True.

## Q8. λs are properties of attractors; they are the same for any initial condition in the basin of attraction.
## Answer: True.

## Q9. Stable and unstable manifolds are unrelated to the eigenvectors of the linearized system.
## Answer: False. it is related.

## Q10. A point on a stable or unstable manifold of a dynamical system stays on that manifold as time evolves.
## Answer: True.

# 7.3 Sections and projections
