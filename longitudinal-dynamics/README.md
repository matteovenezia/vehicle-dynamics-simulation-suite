# Longitudinal Vehicle Dynamics

MATLAB and Simulink model developed to simulate the longitudinal behaviour of a vehicle under traction and braking conditions.

The model includes aerodynamic forces, dynamic load transfer, wheel rotational dynamics, longitudinal tyre forces, slip-ratio calculation and vehicle longitudinal equilibrium.

## Main features

- Longitudinal vehicle dynamics
- Dynamic load transfer
- Aerodynamic drag and lift
- Front and rear wheel rotational dynamics
- Longitudinal tyre-force modelling
- Slip-ratio calculation
- Vehicle speed and acceleration analysis

## Model overview

The figure below shows the top-level Simulink architecture of the longitudinal vehicle dynamics model.

[LongDyn_overview.pdf](https://github.com/user-attachments/files/30300360/LongDyn_overview.pdf)

---

## Model documentation

The complete Simulink model architecture and subsystem hierarchy are available in the PDF below.

[LongDyn.pdf](https://github.com/user-attachments/files/30300366/LongDyn.pdf)

---

## Simulation results

The model was evaluated using a reference speed driving cycle including steady-state cruising, acceleration and braking phases.

### Wheel dynamics

Front and rear wheels angular speed and acceleration.

<img width="1308" height="733" alt="LongDyn_output" src="https://github.com/user-attachments/assets/e970b19b-4425-4724-86c3-ae9a30ec1266" />

### Vehicle speed validation

Comparison between the simulated wheel speed and the reference vehicle speed profile, to correlate the wheel dynamics with the overall vehicle longitudinal response.

<img width="1440" height="850" alt="LongDyn_scope_spd" src="https://github.com/user-attachments/assets/a9e59b63-1bc5-45dc-9323-0036d8ba2686" />

### Vehicle acceleration vaidation

Longitudinal vehicle acceleration, to correlate the wheel angular acceleration with the resulting vehicle response.

<img width="1439" height="719" alt="LongDyn_scope_acc" src="https://github.com/user-attachments/assets/2cba8df0-1e48-41a0-8a07-e42ef08551b6" />
