---
content_type: page
description: This section provides the course notes for each session of the course
  along with summaries of the topics covered.
draft: false
learning_resource_types:
- Lecture Notes
ocw_type: CourseSection
title: Course Notes
uid: ed6fbc8c-33fa-352a-e7bd-2b910c318696
---
The course notes linked below serve as the primary textbook. Each chapter corresponds to the content covered in one lecture session. Note that they are © Professor Hutchinson, all rights reserved, and are not covered by the OCW {{% resource_link "86751090-52e7-433e-8fac-dc99da9f2aa7" "Creative Commons license" %}}.

The notes have also been adapted and published in book form by {{% resource_link "efbed8e7-a9c7-49fd-b5a2-28c1be0b960c" "Cambridge University Press" %}}:

- Hutchinson, Ian. _A Student's Guide to Numerical Methods_. Cambridge University Press, 2015. ISBN: 9781107479500.

{{% resource_link "6e2ad339-8618-4b6a-b52b-cc805d5a8ffd" "Course notes home page, preface, & table of contents" %}}

{{< tableopen >}}{{< theadopen >}}{{< tropen >}}{{< thopen >}}
LEC #
{{< thclose >}}{{< thopen >}}
NOTES
{{< thclose >}}{{< thopen >}}
TOPIC SUMMARIES
{{< thclose >}}{{< trclose >}}{{< theadclose >}}{{< tbodyopen >}}{{< tropen >}}{{< tdopen >}}
1
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "75a27904-6ba5-47ba-8d32-d05015260eef" "Chapter 1: Numerical fitting of data" %}}
{{< tdclose >}}{{< tdopen >}}
1–D least squares fit of a line to a sequence of data. Its representation as a matrix pseudo-inversion problem to determine coefficients.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
2
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "94b3f3f2-6be9-4386-8397-712d652cfbbe" "Chapter 2: Ordinary differential equations (ODEs)" %}}
{{< tdclose >}}{{< tdopen >}}

Ordinary differential equation of order N in one dependent variable is equivalent to N simultaneous first-order ODEs, i.e. a first order vector ODE. The orbit of a field line or an electron in prescribed static EM fields.

Finite difference expressions for derivative. Accuracy and Stability. Implicit and explicit advancing schemes. Runge-Kutta techniques.

Simple Leapfrog scheme as an example of centered time differences.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
3
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "f4dbb1f6-f7b7-4f05-a34d-6a1ca67cdc7b" "Chapter 3: Two-point boundary conditions" %}}
{{< tdclose >}}{{< tdopen >}}

Second order ODES. Two point boundary conditions.

Example(s) of two-point problems: Slab charge, cylindrical volumetrically-heated conduction.

Shooting method. Bisection.

Second order differences. Linear ODE: Expression of 2-point problem as a matrix equation. Finite difference boundary condition implementation in matrix. Non-uniform derivatives.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
4
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "060c0b0a-d4ff-49ff-b13c-ef46f0470ef3" "Chapter 4: Partial differential equations (PDEs)" %}}
{{< tdclose >}}{{< tdopen >}}

Examples of partial differential equations of engineering physics.

Fluid flow and derivation of the continuity equation. Diffusion. Waves. Electromagnetism. Poisson's equation.

Classification of PDEs. Elliptic, Parabolic, Hyperbolic. Consequences for boundary conditions. Finite difference representation of partial derivatives. Structured (and unstructured) meshes. Difference stencil.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
5
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "c1086366-6692-41ba-9623-68ae799b3098" "Chapter 5: Diffusion; parabolic PDEs" %}}
{{< tdclose >}}{{< tdopen >}}

The diffusion equation and boundaries in space and time.

Explicit FTCS scheme for time evolution of multidimensional PDEs first order in time (parabolic). Stability requirement.

Implicit BTCS scheme for time evolution: Unconditionally stable. Crank-Nicholson and θ–implicit schemes.

Expression of the time advance as a matrix equation. Requirement for inversion in implicit schemes. Multidimensional cases leading to non-tridiagonal sparse matrices. The matrix size difficulty for multiple dimensions.

Example of time-dependent diffusive relaxation to a steady state.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
6
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "385479ef-7e21-43f2-96e2-1ac60edd039e" "Chapter 6: Elliptic problems and iterative matrix solution" %}}
{{< tdclose >}}{{< tdopen >}}

Elliptic equation as steady state of a parabolic equation. Need for matrix inversion. Iteration's equivalence to diffusive relaxation. Solving matrix problem without explicit inversion.

Jacobi, Gauss-Seidel and SOR methods. Convergence.

Nonlinear equations, linearization and iteration.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
7
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "da4d68c8-4a09-47b8-8c38-770694a3f319" "Chapter 7: Fluid dynamics and hyperbolic equations" %}}
{{< tdclose >}}{{< tdopen >}}

The fluid momentum conservation equation derived. Fluid closure.

The Navier-Stokes equation in conservation form. Hyperbolic equations in advection form. Eigenvalue of the Jacobian and Characteristics.

Finite differences and stability: FTCS unstable. Lax-Friedrichs and CFL condition. Lax Wendroff, second order accuracy.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
8
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "58179a26-5100-4f6e-806d-02f15ac0191d" "Chapter 8: Boltzmann's equation and its solution" %}}
{{< tdclose >}}{{< tdopen >}}

The distribution function, and flux-density, energy-density.

Boltzmann's equation derivation as an expression of particle conservation in the presence of collisions and sources.

Integration along orbits / characteristics. Vlasov equation distribution behavior.

The collision term. Simple collision process examples.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
9
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "4218ee03-7a17-4e64-8f58-37496e6d5a21" "Chapter 9: Neutron transport" %}}
{{< tdclose >}}{{< tdopen >}}

The Boltzmann equation in terms of flux. Neutron total loss, scattering and fission source terms. Reduction of Boltzmann equation to a (speed-resolved) diffusion equation.

Groups. Multigroup equations and their numerical representation. Leakage. Diffusive timestep stability.

Eigenvalue nature of the steady problem. Power iteration method to solve for dominant eigenvalue.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
10
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "e838da8c-f3e3-419d-9e9d-21721f9151ed" "Chapter 10: Atomistic and particle-in-cell methods" %}}
{{< tdclose >}}{{< tdopen >}}

Atomistic simulation. Time and space scales. Generic approach. Interparticle force examples: Lennard-Jones, Morse. Computational requirements. Neighbor lists and blocks.

The computational problem of long-range forces. Particle in Cell solution for plasmas. Pseudo-particle representation. Phase space. Direct Simulation Monte Carlo (DSMC) treatment of tenuous gas. Boundary conditions and their implementation.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
11
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "670a705d-371b-4f8a-9c13-f0c60c82facd" "Chapter 11: Monte Carlo techniques" %}}
{{< tdclose >}}{{< tdopen >}}
Collisions. Random numbers and statistical distributions. Basic introduction to probability (random variables, pdf, cumulative probability) and statistics (mean, variance, standard error). Random sampling from basic distributions used in Monte Carlo simulations (uniform, exponential, …) and rejection sampling technique. Flux weighted injection.
{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
12
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "f642587f-6b95-4593-988a-ed493fc3c003" "Chapter 12: Monte Carlo radiation transport" %}}
{{< tdclose >}}{{< tdopen >}}

Transport and collisions. Random walk step length; Poisson statistics. Collision-type choice. New particle generation.

Tracking and tallying of collisions. Statistical uncertainty, and tallying methods to reduce it. Importance sampling.

{{< tdclose >}}{{< trclose >}}{{< tropen >}}{{< tdopen >}}
13
{{< tdclose >}}{{< tdopen >}}
{{% resource_link "1991f03d-d9f3-40b5-989e-92f0537aff1e" "Chapter 13: Next steps, e.g. finite elements" %}}
{{< tdclose >}}{{< tdopen >}}
 
{{< tdclose >}}{{< trclose >}}{{< tbodyclose >}}{{< tableclose >}}