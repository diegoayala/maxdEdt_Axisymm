# maxdEdt_Axisymm

This collection of Matlab scripts are used to find axisymmetric flows
that maximize the instantaneous production of enstrophy. 

Discretization is performed via galerkin-fourier and galerkin-chebyshev 
methods. Given the non-constant nature of the differential operators 
involved in the problem, gmres is used whenever possible in order to 
avoid costly matrix construction/inversion.
