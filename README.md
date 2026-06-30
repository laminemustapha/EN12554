# EN12554
# Plug Thickness Computation for Plane Poiseuille--Bingham Flow with Wall Transpiration

This repository contains the implementation accompanying the manuscript on the analytical solution of Bingham fluid flow in a parallel-plate channel with uniform cross-flow.

## Description

The analytical velocity field presented in the manuscript is obtained in closed form. The only numerical step consists of determining the plug thickness, (H), by solving the nonlinear governing equation using a Newton--Raphson iterative method.

This repository provides the scripts required to reproduce the numerical results for the plug thickness reported in the paper.

## Repository Contents

* **HVsBn.m**
  Computes the plug thickness (H) as a function of the Bingham number ((Bn)).

* **HVsRi.m**
  Computes the plug thickness (H) as a function of the cross-flow Reynolds number ((Ri)).

Both scripts include the Newton--Raphson solver and all auxiliary routines required for their execution.

## Requirements

* MATLAB (R2018a or later recommended).

## How to Use

Run either

* `HVsBn.m`

or

* `HVsRi.m`

to reproduce the corresponding numerical results presented in the manuscript.

## Citation

If you use this code in your research, please cite the associated publication.

## License

This project is distributed under the MIT License.
