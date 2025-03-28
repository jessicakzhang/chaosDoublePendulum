# Double Pendulum Simulation

## Description
This project visualizes the chaotic motion of a double pendulum using Python. The simulation numerically solves the equations of motion using the Lagrangian method and animates the results, allowing users to explore the sensitive dependence on initial conditions characteristic of chaotic systems.

## Features
- Solves the double pendulum equations of motion using the Lagrangian formulation.
- Uses `scipy.integrate.odeint` for numerical integration.
- Animates the pendulum motion with `matplotlib.animation`.
- Allows customization of initial conditions, including masses, lengths, and initial angles.
- Visualizes the chaotic behavior of the system through real-time animations.

## Installation
To get started, ensure you have the required dependencies installed:

```bash
pip install numpy matplotlib scipy
