# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The model was validated by the measured ETC and specific surface area of fabricated lunar simulant samples LMS-1. The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
As space exploration becomes continuously attractive, establishing habitats on extraterrestrial planetary bodies is of particular interest. High-temperature ISRU processes driven by concentrated solar energy have been recognized as a potential pathway to provide materials and power for long-term space explorations and construction on the lunar surface. Advantages include: 1) sufficient energy supply; 2) clean and renewable; 3) easing costly transportation issues by using local resources as feedstocks.

## 2. Sintered ETC Modeling
The proposed ETC model is built for a multi-sized particle system using:
- **Coordination Number (CN):** Estimated for poly-sized systems using the Dodds model.
- **Neck Formation:** Simulated via five diffusion processes (surface, volume, grain boundary, and dislocation diffusion).
- **Shape Factor:** Characterized by sphericity and roundness to account for non-spherical regolith geometry.
- **Resistance Analogy:** Heat transfer follows three parallel pathways: solid (Rs), gas (Rg), and radiation (Rrad).

## 3. Experimental Validation
- **Material:** Lunar simulant LMS-1 (simulating lunar mare soil).
- **Conditions:** Samples sintered at 900–1150 °C under air, argon, and vacuum ($10^{-3}$ Pa).
- **Findings:** ETC of sintered samples is 5-20 times higher than green regolith. The model showed an average RMSE of 5.5% for steady-state temperature profiles.

## 4. Heat Transfer in Solar-Sintered Lunar Regolith
A transient solar-sintered heat transfer numerical model was developed based on the Finite Volume Method (FVM) coupled with Monte-Carlo Ray-tracing (MCRT). Results indicate that multi-scaled particles can increase the number of connections and enhance mechanical properties.

## 5. Conclusions
1. An analytical model of sintered LMS-1 thermal conductivity was developed considering neck resistance and irregular shapes.
2. The FVM coupled to the ETC model simulates the update of porous material microstructure and temperature simultaneously.
3. Optimized PSD arrangements can increase sintered depth by 45% compared to original PSD.

### Table 2: Baseline parameters used for ETC modeling (Selection)
| Physical properties (unit) | Value |
| :--- | :--- |
| Radius of small particle (μm) | 15 |
| Radius of medium particle (μm) | 47 |
| Radius of large particle (μm) | 94 |
| Material density (kg/m³) | 3100 |
| Initial porosity | 0.45 |
| Emissivity | 0.925 |