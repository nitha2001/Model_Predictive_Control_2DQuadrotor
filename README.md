# Model_Predictive_Control_2DQuadrotor
This repository implements Model Predictive Control (MPC) for stabilizing a 2D quadrotor. The system is linearized and optimized using quadratic programming (QP) techniques, with constraints on both input saturation and system dynamics.


## Project Overview
This project simulates a 2D quadrotor system using MPC, enforcing:

- State and Input Constraints
- Quadratic Cost Function for control effort minimization
- Linearized System Dynamics enforced through QP optimization
- 
**Relevant Files:**

- `quadrotor.py`: Implements MPC logic, including constraints and cost function.
- `quad_sim.py`: Simulates and visualizes quadrotor behavior.

## Key Concepts
- MPC: Predicts future behavior over a finite horizon and optimizes control actions.
- Quadratic Programming: Solves the MPC as an optimization problem.

## Usage
- Modify initial conditions or system parameters in `quadrotor.py`.
- Implement constraints in the code to match project requirements.
- Run `quad_sim.py` to visualize the quadrotor’s trajectory under MPC.

  ## Results

  
