# PENSDP
PENSDP is a computer program for solving optimization problems with linear objective and linear matrix inequality constraints (linear semidefinite programming problems). It is aimed at large-scale dense and sparse SDP problems. Current version 2.2.

PENSDP was developed by Michal Kočvara and Michael Stingl.

### New in versions 2.1 and 2.2
* Hessian-free version, resulting in significant memory savings
* Iterative solution of the Newton system (optional)
* Stopping criteria based on the DIMACS error measures, resulting in more reliable computations
* Hybrid mode for the solution of the Newton system

### Applications in
* control theory
* relaxations of integer programming problems
* structural optimization
* optimization of eigenvalues
* chemical engineering

### Key features
* aimed at large scale problems
* efficient treatment of different sparsity
patterns in problem data
* detecting infeasibility (MATLAB version)

### It can be used as
* stand-alone program with input file in the
sparse SDPA input format
* MATLAB function with PEN or YALMIP interface (SDPA-to-PEN interface available)
* function called from a C or Fortran program with data communication through parameters

Available as a binary code for major architectures MS Windows, macOS, Linux.
