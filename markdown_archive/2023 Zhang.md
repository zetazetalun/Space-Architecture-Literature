# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The model was validated by measured ETC and specific surface area of fabricated lunar simulant samples LMS-1. Furthermore, the heat transfer process within solar sintered LMS-1 bed was simulated. The simulated temperature profiles at the steady state concur well with measured data (RMSE=5.5%). The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
Establishing habitats on extraterrestrial planetary bodies is of particular interest. High-temperature ISRU processes driven by concentrated solar energy have been recognized as a potential pathway to provide materials and power for construction on the lunar surface. Advantages include: 1) sufficient energy supply; 2) clean and renewable; 3) easing costly transportation issues by applying local resources (lunar regolith).

## 2. Sintered ETC Modeling
The proposed ETC model is built on a multi-sized particle system using the Monte-Carlo method. 
- **Coordination Number (CN):** Estimated for poly-sized particle systems using the Dodds model and modified for gaps using Suzuki's model.
- **Solid Particle Conduction:** Simulated based on heat flow through porous media and sintering necks.
- **Diffusion Mechanisms:** Five types (boundary, volume from surface, volume from grain boundary, surface, and volume from dislocation) are parameterized for neck growth rate.
- **Gas and Radiative Conductivity:** Included to account for atmospheric testing environments and internal radiation.

## 3. Experimental Validation
LMS-1 samples were fabricated under air, argon, and vacuum (10^-3 Pa). 
- **Specific Surface Area:** Decreases with increasing sintering temperature due to neck growth. Mean error of 20.9%.
- **ETC Results:** Sintered samples' ETC was 5-20 times higher than green samples. RMSE for sintered samples was 12.1% to 13.7% for different granularities.

## 4. Heat Transfer in Solar-Sintered Lunar Regolith
A transient solar-sintered heat transfer numerical model was developed using the Finite Volume Method (FVM) coupled with Monte-Carlo Ray-tracing (MCRT). 
- **Solar Simulator:** Peak radiation flux of ~265 kW/m^2.
- **Findings:** Measured and modeled temperatures match with RMSE of 5.5% in steady state. Sintering significantly impacts heat transport compared to un-sintered models (RMSE=12.7%).

## 5. Conclusions
1. An analytical model of sintered LMS-1 thermal conductivity was developed and validated.
2. Optimized PSD (stacking fine particles on top of medium/large particles) improved the sintered depth by 45% (from 18mm to 26mm).
3. The model provides a theoretical foundation for thermal performance evaluation of high-temperature lunar ISRU processes.