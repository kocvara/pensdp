# PENSDP
PENSDP is a computer program for solving optimization problems with linear objective and linear matrix inequality constraints (linear semidefinite programming problems). It is aimed at large-scale dense and sparse SDP problems. Current version 2.2.

PENSDP was developed by Michal Kočvara and Michael Stingl.

### This repository contains
* precompiled libraries for Windows 64, MacOS 64 (Intel and ARM) and Linux 64bit in directory **bin**
* User's guide for installation and use in directory **doc**. *Please read this first.*

### PENSDP can be used as
* stand-alone program with input file in the
sparse SDPA input format
* MATLAB function with PEN or YALMIP interface (SDPA-to-PEN interface available)
* function called from a C or Fortran program with data communication through parameters

### Key features
* aimed at large scale problems
* efficient treatment of different sparsity patterns in problem data
* detecting infeasibility (MATLAB version)

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

### Reference
    
M. Ko&#269;vara and M. Stingl. On the solution of large-scale SDP
problems by the modified barrier method using iterative solvers. *Mathematical Programming Series B*, 109(2-3):413-444, 2007.
