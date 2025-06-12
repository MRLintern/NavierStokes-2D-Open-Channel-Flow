
## 2D Navier-Stokes Equations Solver for 2D Open Channel Flow
### Introduction
* This solver, developed in `Fortran 2008`, solves the ___2D Navier-Stokes Equations___ for a __fluid flowing__ in an __Open-Channel__ which can be thought of as a ___river___.
* The __Finite Volume Method (FVM)__ has been used to __discretisise__ the __2D Navier-Stokes Equations__.
* The solver has been __parallelised__ using `coarrays` and the resulting __Algebraic Equations__ from __discretisation__ are solved via the __Successive Over Relaxation Method (SOR)__.
* The __problem-domain__ is divided up using ___Domain Decomposition___.

### Theory
* 
#### Domain Decomposition
* 
### Requirements
* __Compiler__: `gfortran`.
* __OS__: Developed and test on `Ubuntu 20.04`.
* `Make` to build the software.
### Getting and Running the Software

### References
* ___Modern Fortran: Building Efficient Parallel Applications___ by __Milan Curcic__.
