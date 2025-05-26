##  Assignment Overview

This notebook focuses on stabilizing the classic cart-pole system. It combines nonlinear system modeling with modern control techniques such as linearization, linear feedback, observer design, and discrete control. Both analytical derivations and simulations are used to validate control strategies.

## 💡 Alternative way to check the solution  
[Open in Google Colab](https://drive.google.com/file/d/1e7x1JWJuO-cjQD8zoA9OjirNroEz5nBj/view?usp=share_link)  

If the file `Control_theory_assigment_3.ipynb` does not display fully.


### Objectives:

1. Derive the nonlinear dynamics of the cart-pole system using the Lagrangian method.
2. Linearize the dynamics around the upright equilibrium point.
3. Design a linear state feedback controller for the linearized system using pole placement.
4. Simulate and compare system response for both linearized and original nonlinear dynamics.
5. Design a state observer assuming only output $y = Cx$ is measured.
6. Implement observer-based feedback and simulate system behavior.
7. Demonstrate the effect of estimation error versus true state.
8. Discretize the nonlinear system using a fixed time step.
9. Design a discrete controller (both via pole placement and LQR).
10. Simulate closed-loop discrete-time behavior and verify stability.

The notebook includes both symbolic derivations and numeric simulations, making it a comprehensive example of modern control system design for underactuated nonlinear systems.
