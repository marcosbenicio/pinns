# Physical Informed Neural Network (PINN)

This repository contains Jupyter Notebook files that implement physics-informed neural networks (PINNs) using TensorFlow library. The examples in this repository are based on the paper "Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations" by M. Raissi et al. (2019).

## Contents

- pinn_burgers.ipynb: This notebook demonstrates how to use a PINN to solve the Burgers' equation, a nonlinear partial differential equation that arises in fluid mechanics. The notebook includes a step-by-step walkthrough of the code, along with explanations of key concepts.

- pinn_stokes.ipynb: This notebook demonstrates how to use a PINN to solve the Stokes equation, which describes the flow of viscous fluids. Note that the code for this example is incomplete and currently has a problem with the L_BFGS_B optimizer that has not yet been resolved.

## References
The examples in this repository are based on the following paper:

Raissi, M., Perdikaris, P., & Karniadakis, G. E. (2019). Physics-informed neural networks: A deep learning framework for solving forward and inverse problems involving nonlinear partial differential equations. Journal of Computational Physics, 378, 686-707. doi:10.1016/j.jcp.2018.10.045
