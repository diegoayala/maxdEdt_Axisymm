# maxdEdt_Axisymm

This collection of Matlab scripts is used to find axisymmetric flows
that maximize the instantaneous production of enstrophy in the 3D
Navier-Stokes equation.

Discretization is performed via Galerkin-Fourier and Galerkin-Chebyshev 
methods. Given the non-constant nature of the differential operators 
involved in the problem, GMRES is used whenever possible in order to 
avoid costly matrix construction/storage/inversion.
