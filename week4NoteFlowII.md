# 4.1 Fixed points and stability
* Q1. Do conservative systems have attractors?
 Answer: No. (not always true)
* Q2. Can conservative systems be chaotic?
 Answer: Yes. (Yes it can)
* Q3. How do you know if a point is a fixed point of the dynamics?
 - A. The trajectory starts there
 - B. Trajectories never leave that state
 - C. If the system is at that state and you perturb it, that perturbation will shrink
 - Answer: B
* Q4. How do you know if a point is a stable fixed point of the dynamics?
- A. The trajectory starts there
- B. Trajectories never leave that state
- C. If the system is at that state and you perturb it, that perturbation does not grow and trajectories never leave that state without external influence
- Answer: C
 

# 4.2 Saddle points and eigenvectors
* Q1. All fixed points live in the bottoms of bowls in the dynamical landscape.
Answer: False
* Q2. The following fixed points of the undamped pendulum are saddle points in the dynamical landscape (i.e., with one positive real eigenvalue and one negative real eigenvalue).
* (a) <a href="https://www.codecogs.com/eqnedit.php?latex=(\theta$,\omega)=(0,0)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\theta$,\omega)=(0,0)" title="(\theta$,\omega)=(0,0)" /></a> <br />
Answer: False
* (b) <a href="https://www.codecogs.com/eqnedit.php?latex=(\theta,\omega)=($\pi$,0)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\theta,\omega)=($\pi$,0)" title="(\theta,\omega)=($\pi$,0)" /></a> <br />
Answer: True

* (c) <a href="https://www.codecogs.com/eqnedit.php?latex=(\theta,\omega)=(3$\pi$,0)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\theta,\omega)=(3$\pi$,0)" title="(\theta,\omega)=(3$\pi$,0)" /></a> <br />
Answer: True

* (d) <a href="https://www.codecogs.com/eqnedit.php?latex=(\theta,\omega)=(-$\pi$,0)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\theta,\omega)=(-$\pi$,0)" title="(\theta,\omega)=(-$\pi$,0)" /></a> <br />
Answer: True

* (e) <a href="https://www.codecogs.com/eqnedit.php?latex=(\theta,\omega)=(2$\pi$,0)" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(\theta,\omega)=(2$\pi$,0)" title="(\theta,\omega)=(2$\pi$,0)" /></a> <br />
Answer: False

* Q3. Calculate the eigenvalues s1 and s2 of this matrix:<br />
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;4&space;&&space;1&space;\\&space;2&space;&&space;3&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;4&space;&&space;1&space;\\&space;2&space;&&space;3&space;\end{bmatrix}" title="\begin{bmatrix} 4 & 1 \\ 2 & 3 \end{bmatrix}" /></a> <br />
Answer: s=5,2
<br />
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;4-s&space;&&space;1&space;\\&space;2&space;&&space;3-s&space;\end{bmatrix}&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;4-s&space;&&space;1&space;\\&space;2&space;&&space;3-s&space;\end{bmatrix}&space;=&space;0" title="\begin{bmatrix} 4-s & 1 \\ 2 & 3-s \end{bmatrix} = 0" /></a>
<br />
<a href="https://www.codecogs.com/eqnedit.php?latex=(4-s)(3-s)-2&space;=&space;0&space;\\&space;s^2-7-10&space;=&space;0&space;\\&space;(s-5)(s-2)&space;=&space;0" target="_blank"><img src="https://latex.codecogs.com/gif.latex?(4-s)(3-s)-2&space;=&space;0&space;\\&space;s^2-7-10&space;=&space;0&space;\\&space;(s-5)(s-2)&space;=&space;0" title="(4-s)(3-s)-2 = 0 \\ s^2-7-10 = 0 \\ (s-5)(s-2) = 0" /></a>

* Q4. What is the shape of this matrix? <br />
<a href="https://www.codecogs.com/eqnedit.php?latex=\begin{bmatrix}&space;0&space;&&space;9.2&&space;\pi&&space;\e&space;&&space;7&space;\\&space;18&space;&&space;3&space;&&space;12&space;&&space;-8.2&space;&&space;2\pi&space;\end{bmatrix}" target="_blank"><img src="https://latex.codecogs.com/gif.latex?\begin{bmatrix}&space;0&space;&&space;9.2&&space;\pi&&space;\e&space;&&space;7&space;\\&space;18&space;&&space;3&space;&&space;12&space;&&space;-8.2&space;&&space;2\pi&space;\end{bmatrix}" title="\begin{bmatrix} 0 & 9.2& \pi& \e & 7 \\ 18 & 3 & 12 & -8.2 & 2\pi \end{bmatrix}" /></a>
<br />
Answer: 2x5

* Q5. A is a 2x2 matrix that captures how the state of a dynamical system evolves.  How many eigenvalues does A have?  (Experts: count any repeated ones individually.) 
Answer: 2

* Q6. A is a matrix that captures how the state of a dynamical system evolves.  Any point on an eigenvector of A ..... stay on that eigenvector.
Answer: B. Must

* Q7. A is a 2x2 matrix that captures how the state of a dynamical system evolves.  If the eigenvalues of A are negative, what kind of dynamics does that reflect?  (Experts: assume that they're real-valued.)
Answer: Fixed point

* Q8. An eigenvalue defines:
Answer: B. How fast a trajectory moves along the corresponding eigenvector

* Q9. A matrix can give you an accurate representation of the evolution of the state of a linear dynamical system.
Answer: A. True

* Q10. A matrix can give you an accurate local representation of the evolution of the state of a nonlinear dynamical system.
Answer: A. True

* Q11. A matrix can give you an accurate global representation of the evolution of the state of a nonlinear dynamical system.
Answer: B. False

# 4.3 Stable and unstable manifolds
heteroclinic cycle, [homoclinic cycle](https://en.wikipedia.org/wiki/Homoclinic_bifurcation).
* Q1. A fixed point in a two-dimensional linear dynamical system that has one positive real eigenvalue and one negative real eigenvalue is a saddle point.
 - True.
* Q2. A fixed point in a two-dimensional nonlinear dynamical system that has one positive real eigenvalue and one negative real eigenvalue is a saddle point.  (Experts: assume that the nonlinear system can be linearized at the fixed point.)
 - Answer: True
* Q3. The point Θ = π, ω = 0 in the pendulum is a saddle point.
 - Answer: True
* Q4. The point Θ = π, ω = 0 is the pendulum's only saddle point.
 - Answer: False
* Q5. Stable and unstable manifolds are the same thing as stable and unstable eigenvectors.
 - Answer: False
* Q6. A point that starts on an unstable manifold will always stay on that unstable manifold.
 - Answer: True
* Q7. The distance between a fixed point and a point near that fixed point on its stable manifold will grow with time.
 - Answer: False
* Q8. The distance between a fixed point and a point near that fixed point on its unstable manifold will grow with time.
 - Answer: True
* Q9. If a fixed point's stable manifold connects back around and becomes its own unstable manifold, that's called a heteroclinic orbit.
 - Answer: False.

# 4.4 Attractors, strange and otherwise
* Q1. Stable and unstable manifolds play no role in the shape of a chaotic attractor.
* Q2. Stable manifolds have the effect of compressing state space.
* Q3. Unstable manifolds have the effect of compressing state space.
* Q4. An attracting fixed point in an n-dimensional nonlinear dynamical system lives at the intersection of n stable manifolds.
* Q5.
Here's a picture of a periodic orbit of a nonlinear dynamical system.

![The picture](https://github.com/Taiyou/NonLinearDynamics/blob/master/content_periodic-orbit.jpg)

What can you say, from the picture above, about the dimension of that system?
 - A. Nothing
 - B. The state space has one dimension
 - C. The state space has two dimensions
 - D. The state space has at least three dimensions
 - E. The periodic orbit is an attractor
* Q6. There is at least one stable manifold associated with every point on an attracting periodic orbit in a nonlinear dynamical system.
* Q7. The Lorenz system has three state variables and two parameters.
* Q8. The Lorenz system models a spring-loaded pendulum (like the simple harmonic oscillator on a pivot).
* Q9. There are two stable fixed points in the dynamics of the Lorenz system for some values of the system's parameters.
* Q10. There is a chaotic attractor in the dynamics of the Lorenz system for some values of the system's parameters.
* Q11. Nonlinear dynamical systems can have lots of attractors in different regions of their state space, but only one type at a time (i.e. all fixed points, all periodic orbits, or all chaotic attractors).
* Q12. The basins of attraction of different attractors in a dynamical system can overlap.
* Q13. Lorenz was the first person to recognize chaos.  (Experts: neglect Poincare, who did a lot of things before others did, including write down e=mc2!)
* Q14. Lorenz was the first person to use the term "chaos" for this kind of behavior.

# 4.5 Field trip: Using stable and unstable manifolds to design spacecraft trajectories (with Jeff Parker) 
