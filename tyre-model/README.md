# Pacejka 98 Tyre Model

MATLAB and Simulink implementation of the Pacejka 98 Magic Formula tyre model for longitudinal and lateral tyre-force prediction.

The model computes longitudinal and lateral tyre forces as functions of slip ratio, slip angle, vertical load and camber angle, including combined-slip behaviour through an elliptical friction model. The tyre model is designed to be integrated into higher-level vehicle dynamics simulations. :contentReference[oaicite:0]{index=0}

## Main features

- Pacejka 98 Magic Formula implementation
- Longitudinal tyre-force modelling
- Lateral tyre-force modelling
- Combined-slip formulation
- Elliptical friction model
- Vertical load sensitivity
- Camber angle effects
- Slip-ratio and slip-angle relaxation

## Model overview

The figure below shows the top-level Simulink architecture of the tyre model.

[pacejka98_overview.pdf](https://github.com/user-attachments/files/30300944/pacejka98_overview.pdf)

---

## Model documentation

The complete Simulink model architecture and subsystem hierarchy are available in the PDF below.

[pacejka98.pdf](https://github.com/user-attachments/files/30300954/pacejka98.pdf)

---

## Model integration

The tyre model provides the longitudinal and lateral tyre forces (**Fx** and **Fy**) used by the longitudinal and lateral vehicle dynamics models contained in this repository.

The implementation includes:

- Slip-ratio and slip-angle computation with relaxation effects.
- Pacejka 98 longitudinal and lateral Magic Formula models.
- Combined-slip correction through an elliptical friction model.
- Longitudinal and lateral tyre-force outputs for vehicle dynamics simulations.
