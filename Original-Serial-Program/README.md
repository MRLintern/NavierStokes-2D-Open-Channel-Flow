## Original Software
* This folder contains the original software developed some 4 years ago.
* Its kept here for reference.

## 2D Navier-Stokes Equations Solver for 2D Open Channel Flow
This code solves the Navier-Stokes Equations for 2D Open Channel Flow.
The equations are discretized using the finite volume method.
The Resulting System of Algebraic Equations is solved using the Successive Over-Relaxation (SOR) Method

## Requirements
* Compiler: `gfortran`. If you don't have it, get it from [here](https://gcc.gnu.org/fortran/).
### Installing gfortran
1. Update: `$ sudo apt-get update`
2. Install: `$ sudo apt-get install gfortran-9`
* Developed on `Ubuntu 20.04`.
* `Make`. If you don't have it, get it from [here](https://www.gnu.org/software/make/).
### Installing Make
1. Update: `$ sudo apt-get update`
2. Install: `$ sudo apt-get install make`

## Getting and Running the Application
1. Clone the repository: `$ git clone https://github.com/MRLintern/NavierStokes-2D-ChanelFlow.git`
2. `$ make`
3. `$./NavierStokes-2D-ChanelFlow`

## Results
* Once the program has been run, a file called `RESULTS.dat` will be generated
with the solution.
* For visualization, [ParaView](https://www.paraview.org/) is a good choice.
* If you need help go to [ParaView Tutorial](https://www.paraview.org/Wiki/images/b/bc/ParaViewTutorial56.pdf).
* If you don't want to run the program, `RESULTS.dat` is included.
* You can save the output data to CSV instead; change it in the source file. I've used CSV files for **ParaView**; never checked if dat files can be used but they probably can be. 

## TODO
* Tried running the application again after some time away; problems r.e. saving output data; to be fixed.
Employ OOP.
