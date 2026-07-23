# Lateral Vehicle Dynamics

MATLAB and Simulink full-vehicle model based on a three-degree-of-freedom (3-DoF) formulation, developed to simulate the lateral behaviour of a vehicle during cornering manoeuvres.

It combines a 3-DoF vehicle dynamics formulation with four-wheel tyre force modelling, wheel rotational dynamics, aerodynamic loads and global trajectory reconstruction.

## Main features

- Full-vehicle 3-DoF lateral dynamics
- Four-wheel tyre-force modelling
- Tyre slip-angle calculation
- Wheel rotational dynamics
- Aerodynamic forces and moments
- Yaw dynamics
- Global vehicle trajectory reconstruction
- Handling response analysis

## Model overview

The figure below shows the top-level Simulink architecture of the lateral vehicle dynamics model.

[LatDyn_overview.pdf](https://github.com/user-attachments/files/30300732/LatDyn_overview.pdf)

---

## Model documentation

The complete Simulink model architecture and subsystem hierarchy are available in the PDF below.

[LatDyn.pdf](https://github.com/user-attachments/files/30300737/LatDyn.pdf)

---

## Simulation results

The model was evaluated during a constant-radius cornering manoeuvre with progressively increasing steering input.

The following figures summarize the main vehicle response:

- **Steering characteristic:** steering angle as a function of lateral acceleration.
- **Sideslip characteristic:** vehicle sideslip angle as a function of lateral acceleration.
- **Vehicle trajectory:** global vehicle trajectory reconstructed from the simulated vehicle states.
- **Vehicle speed profile:** vehicle speed evolution throughout the cornering manoeuvre.


<img width="1440" height="801" alt="LatDyn_output" src="https://github.com/user-attachments/assets/01de1567-6049-49ee-a4a4-f1abdc2427c6" />
