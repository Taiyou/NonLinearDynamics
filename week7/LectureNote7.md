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
## Q1. Both projections and sections reduce the dimension of an object.
## Answer: True

## Q2. A medical x-ray performs a projection operation.
## Answer: True.

## Q3. Meauring the value of a single state variable of a dynamical system is like performing a section.
## Answer: False.

## Q4. Sections can be slices in time or slices in (state) space.
## Answer: True.

## Q5. Consider the following orbit of a dynamical system (in blue in the following figure).
### (a) What will you see if you perform a spatial Poincare section of this object with a plane of section x = 3?
#### A. A middle-half removed Cantor set
#### B. An equally spaced circle of points
#### C. Two points
#### D. Four points
#### E. One point
#### Answer: C. Two points

### (b) What type of dynamics is this type of section associated with?
#### A. 2-cycle
#### B. 4-cycle
#### C. Chaos
#### D. Fixed point
#### Answer: A. 2-cycle

### (c) What will you see if you perform a spatial Poincare section of this object with a plane of section y = 2?
#### A. A middle-half removed Cantor set
#### B. An equally spaced circle of points
#### C. Two points
#### D. Four points
#### E. One point
#### Answer: D. Four points

### (d) What type of dynamics is this type of section associated with?
#### A. 2-cycle
#### B. 4-cycle
#### C. Chaos
#### D. Fixed point
#### Answer: B. 4-cycle

# 7.4 Unstable periodic orbits.
  - Unstable periodic orbits (UPOs)
    - if perterbations disturb periodic activity
  - strange or chaotic attractors:
    - exponential divergence of neighboring trajectories
    - often fractal
    - covered densely by trajectories
    - contain an infinite number of unstable periodic orbits
  - [Poincare recurrence](https://en.wikipedia.org/wiki/Poincar%C3%A9_recurrence_theorem)

## Q1. How many unstable periodic orbits (UPOs) are there in the dynamical landscape of a dissipative chaotic system?
### A. None
### B. An infinite number
### C. It depends on which chaotic system you're talking about
### Answer: B. An infinite number

## Q2. All UPOs have even-numbered periods (2, 4, 6, ...)
### Answer: False. any natural numbers.

## Q3. Which of the following statements are true about the relationship between UPOs and chaotic attractors?
### A. A chaotic attractor is the closure of the set of its UPOs
### B. UPOs are dense in any chaotic attractor
### C. Both of the above
### D. Neither of the above
### Answer: C. Both of the above

# 7.5 Fractal and chaos
  - most chaotic sysmtes have fractral structure, but not all.
  - cantor set
    - middle third Cantor set
    - cantor set is "self similar"
  - capacity dimension aka box dimension
    - Eucledean norm
    - L1

## Q1. Fill in the blank. [...] chaotic systems have fractal state-space structure.
### A. Only a few
### B. All
### C. Most
### Answer: C. Most

## Q2. (Experts: Almost all) fractals have non-integer fractal dimension.
### Answer: True. 

## Q3. (Experts: Almost all) fractals are self similar objects.
### Answer: True.

## Q4. The fractal dimension of the middle-fifth-removed Cantor set is smaller than that of the middle-third-removed Cantor set.
### Answer: B. False

## Q5. 
### Answer: B.

## Q6. What is the capacity dimension of the middle-third-removed Cantor set?
### A. 0.6309
### B. 
### C. 0.3333
### D. 0.8614
### Answer: A. 0.6309

## Q7. What is the capacity dimension of the middle-fifth-removed Cantor set?
####  0.6309
### B. 
### C. 0.2
### D. 0.7565
### Answer: D. 0.7565
