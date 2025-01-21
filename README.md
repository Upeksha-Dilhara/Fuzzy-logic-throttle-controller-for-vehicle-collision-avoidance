# Fuzzy Logic Throttle Controller for Vehicle Collision Avoidance

This repository contains the implementation of a Fuzzy Logic Controller (FLC) for a vehicle throttle system designed to avoid collisions. The controller uses MATLAB for simulation and evaluation.

## Project Overview

It aims to control the throttle of a vehicle based on the distance to an obstacle and the vehicle's speed, ensuring safe operation by reducing the throttle as necessary to avoid collisions.

### Inputs
1. **Distance to obstacle (m)**
2. **Speed (km/h)**

### Output
- **Throttle (%)**

## Features
1. Identification of fuzzy sets for input and output variables.
2. Definition of fuzzy control rules using the Mamdani inference method.
3. Computation of fuzzy memberships and throttle values for given inputs.
4. Visualization of the control surface to evaluate the system's quality.
5. Implementation of a simple vehicle model to simulate the FLC in MATLAB.
6. Simulation results for five different initial conditions.

## Key Components

### Fuzzy Sets

#### Distance to Obstacle (m):
- **Very Close**: 0-20
- **Close**: 10-40
- **Medium**: 30-60
- **Far**: 50-80
- **Very Far**: 70-80

#### Speed (km/h):
- **Slow**: 0-90
- **Medium**: 90-180
- **Fast**: 90-180

#### Throttle (%):
- **No Throttle**: 0-30
- **Low Throttle**: 10-40
- **Medium Throttle**: 30-70
- **High Throttle**: 60-90
- **Full Throttle**: 80-100

### Control Rules

<p align="justify"> The Fuzzy Logic Controller (FLC) utilizes 15 rules to map the inputs—vehicle speed and distance to obstacles—to the throttle output, ensuring precise and safe control. The system's effectiveness is demonstrated through simulations conducted under five different initial conditions, highlighting its ability to manage throttle adjustments for collision avoidance. Results from these simulations include detailed plots showing variations in speed, distance to the obstacle, and throttle over time, providing a clear visualization of the controller's performance under diverse scenarios. </p>


