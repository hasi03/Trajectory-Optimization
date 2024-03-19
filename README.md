# Trajectory-Optimization
Exploring various numerical methods to solve orbital mechanics of satellites.


## Overview
This project is focused on solving the orbital equations of motion for the Henon-Heiles system, a classic problem in astrophysics and chaos theory. We employ three different numerical methods to integrate these equations and present visual comparisons of the results.

## Methods Used
- **Verlet Integration**: A simple yet powerful method for integrating Newton's equations of motion, which is particularly useful for conservative systems.
- **Heun's Method**: An explicit predictor-corrector method for solving ordinary differential equations, providing a balance between simplicity and accuracy.
- **(Third Method)**: The notebook outlines a third method employed in the analysis, tailored for solving the specific system at hand.

## Key Features
- **Equation of Motion**: Derivation and implementation of the equations governing the Henon-Heiles system.
- **Initial Conditions**: Exploration of the impact of varying initial conditions on the system's dynamics.
- **Integration**: Implementation of three distinct numerical methods to solve the equations of motion.
- **Visualization**: Comprehensive plots comparing the trajectories obtained through each numerical method, illustrating the system's behavior under different initial conditions.

## Getting Started
To run this project, ensure you have Jupyter Notebook installed and that your environment supports Python 3.x. The notebook makes use of common scientific computing libraries such as NumPy and Matplotlib for numerical analysis and visualization.

1. Clone this repository to your local machine.
2. Navigate to the repository's directory.
3. Run `jupyter notebook` in your terminal.
4. Open  from the Jupyter Notebook interface.
5. Execute the cells sequentially to observe the project's results.

## Requirements
- Python 3.x
- NumPy
- Matplotlib
- Jupyter Notebook

## Contributing
We welcome contributions and suggestions to improve the analysis and expand the scope of this project. Feel free to fork the repository, make your changes, and submit a pull request.
