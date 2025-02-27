# 4-DOF Robotic Arm Project

## Project Description
This project involves the design, modeling, and implementation of a 4-Degree-of-Freedom (DOF) robotic arm as part of the "Design and Modeling of Robotic Systems" course at the EuroMed University of Fez. The primary objective is to develop a robotic arm capable of precise manipulation, integrating mechanical design, kinematic analysis, electronic control, and software programming.

The project follows a structured approach, including:
- CAD-based mechanical design
- Kinematic analysis using forward and inverse kinematics
- 3D printing for prototyping and fabrication
- Embedded system integration using Raspberry Pi 4
- Software control using Python
- Simulation using RViz

Despite constraints in time and resources, this project serves as a valuable hands-on experience in robotics engineering, with potential applications in industrial automation and object manipulation.

## Table of Contents
1. Executive Summary
2. Introduction
   - Context and Motivation
   - Project Objectives
3. Mechanical Design
   - Degrees of Freedom (DOF) Analysis
   - CAD Modeling
   - Actuation System
4. Kinematics
   - Forward Kinematics
   - Inverse Kinematics
   - Denavit-Hartenberg Parameters
5. Prototyping and Fabrication
   - 3D Printing and Assembly
6. Electronics and Control Architecture
   - Microcontroller Selection
   - Motor Control
7. Software and Simulation
   - Python-Based Programming
   - RViz Simulation
8. Constraints and Limitations
9. Results and Discussion
10. Conclusion and Future Work

## Installation and Setup
### Hardware Requirements
- Raspberry Pi 4
- MG995 and MG90 Servomotors
- 3D-printed robotic arm components
- Power supply and necessary wiring

### Software Requirements
- Python 3.x
- Raspberry Pi OS
- ROS (Robot Operating System) for simulation
- RViz for visualization

### Steps to Run the Project
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/4dof-robotic-arm.git
   cd 4dof-robotic-arm
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the control script:
   ```bash
   python control.py
   ```
4. To visualize the robotic arm in RViz:
   ```bash
   roslaunch robotic_arm display.launch
   ```

## Contributors
- Omar EL ALAOUI
- Mohamed BOFARHA
- Bouarfa LAHMR
- Hiba MOUHSINE

## Supervisor
- Prof. Zakaria Chalh

## License
This project is licensed under the MIT License - see the LICENSE file for details.
