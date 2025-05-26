##  Assignment Overview

This notebook includes a series of control theory tasks focused on converting differential equations to state-space and transfer function form, performing numerical simulations, and analyzing system stability.

## Alternative way to check solution
https://colab.research.google.com/drive/1cJeABfz1I5gAt-4Hzicu0JChjeI2rPuU?usp=share_link

If the file fails to display fully

###  Task Summaries

####  Task 1.1: ODE to State-Space Conversion
**Objective:** Convert two 4th-order linear differential equations into state-space and transfer function representations.  
**Implementation:**  
- Normalized equations by the highest-order derivative.
- Introduced state variables $( x_1 = y, x_2 = \dot{y}, \ldots $).
- Constructed state matrix $A$ and input matrix $B$.
- Derived transfer function $(G(s) = \frac{Y(s)}{U(s)}$).

####  Task 1.2: Second-Order ODE and Transfer Function
**Objective:** Reduce a given system to a second-order ODE and construct its transfer function.  
**Implementation:**  
- Symbolically manipulated a system with multiple inputs.
- Derived second-order ODE and corresponding transfer function.

####  Task 1.3: Numerical Integration
**Objective:** Implement Euler or Runge-Kutta integration to solve the ODE from Task 1.  
**Implementation:**  
- Implemented the Euler method.
- Simulated and visualized the solution over time.

####  Task 2.1: Multi-Input State-Space Simulation
**Objective:** Convert a multi-input system to state-space form and simulate its behavior.  
**Implementation:**  
- Built state matrices for a system with three inputs.
- Simulated system dynamics using Python.

####  Task 3.1: Transfer Function Construction
**Objective:** Convert given differential equations into transfer functions.  
**Implementation:**  
- Used Laplace transform properties.
- Derived $G(s) $ for each input-output relationship.

####  Task 4.1: Stability of Autonomous Systems
**Objective:** Determine if the given autonomous linear systems are stable.  
**Implementation:**  
- Computed eigenvalues of the system matrix.
- Assessed stability based on sign of real parts (Re(λ) < 0).

####  Task 4.2: Stability Simulation
**Objective:** Simulate the systems from Task 4.1 to verify convergence to zero.  
**Implementation:**  
- Generated phase portraits.
- Numerically confirmed system stability.

####  Task 4.3: Convergence with Constant Input
**Objective:** Add a constant term to the system and show how the convergence point changes.  
**Implementation:**  
- Included a constant vector $b$ in the system.
- Simulated the new steady-state behavior for different constants.
