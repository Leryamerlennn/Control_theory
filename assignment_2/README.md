## Assignment Overview

This notebook explores advanced topics in control theory including transfer function analysis, state feedback design using pole placement and LQR, simulation of closed-loop dynamics, and discrete-time control system design.

## Alternative way to check the solution  
[Open in Google Colab](https://drive.google.com/file/d/1-LLhy79aaLsyXelYzcoETNAdrOl_Kx2d/view?usp=share_link)  

If the file `Control_theory_assigment_2.ipynb` does not display fully.

###  Task Summaries

####  Task 1: Transfer Function Representation  
**Objective:** Derive the transfer function $W(s) = \frac{Y(s)}{U(s)}$ from the state-space model.  
**Implementation:**  
- Computed $(sI - A)^{-1}$ analytically using the adjugate method.  
- Applied $W(s) = C(sI - A)^{-1}B + D$.

####  Task 2: ODE Representation  
**Objective:** Express the given state-space system as a higher-order differential equation.  
**Implementation:**  
- Eliminated state variables to form a single-output differential equation.

####  Task 3: State Feedback Controller via Pole Placement  
**Objective:** Design a stabilizing controller $u = -Kx$ using pole placement.  
**Implementation:**  
- Chose desired poles.  
- Computed gain matrix $K$ using symbolic tools.

####  Task 4: State Feedback via LQR  
**Objective:** Design controller using Linear-Quadratic Regulator.  
**Implementation:**  
- Defined cost function $J = \int (x^T Q x + u^T R u)\, dt$.  
- Solved Riccati equation and derived optimal gain matrix $K$.

####  Task 5: Closed-Loop Stability  
**Objective:** Validate the stability of the closed-loop system.  
**Implementation:**  
- Computed eigenvalues of the closed-loop matrix $A - BK$.

####  Task 6: Frequency Domain Stability Margins  
**Objective:** Evaluate gain and phase margins using the Bode plot.  
**Implementation:**  
- Generated Bode diagram and interpreted stability margins.

####  Task 7: Simulation of Closed-Loop Dynamics  
**Objective:** Simulate system behavior with the designed controller.  
**Implementation:**  
- Performed time-domain simulation.  
- Visualized convergence to equilibrium.

####  Task 8: Control Law for Target State Tracking  
**Objective:** Modify control to ensure convergence to a non-zero state $x_0$.  
**Implementation:**  
- Adjusted control law to include a feedforward term.  
- Simulated and plotted both state and error dynamics.

####  Task 9: System Discretization  
**Objective:** Discretize the system with $\Delta t = 0.01$.  
**Implementation:**  
- Derived discrete-time matrices $A_d, B_d$ using matrix exponential and zero-order hold.

####  Task 10: Discrete-Time Control Design  
**Objective:** Design discrete controller via pole placement and LQR.  
**Implementation:**  
- Applied discrete pole placement.  
- Defined cost matrices $Q, R$ for discrete LQR and solved the Riccati difference equation.


