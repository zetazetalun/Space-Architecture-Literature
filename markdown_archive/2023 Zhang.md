# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Most existing literature has been focused on the packed lunar regolith without considering the sintering mechanism. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The presented model was experimentally validated by the measured ETC and specific surface area of fabricated lunar simulant samples LMS-1 with various granularities sintered under air, argon gas and low vacuum ($10^{-3}$ Pa). Furthermore, the heat transfer process within solar sintered LMS-1 bed was simulated coupled with the ETC model. Transient behaviors of microstructure, thermal conductivity and temperature profile during solar heating were simulated iteratively. The simulated temperature profiles at the steady state concur well with measured data obtained from the solar sinter testing with an average Root Mean Squared Error (RMSE) of 5.5%, which performs better than the un-sintered ETC model (RMSE=12.7%). The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
As space exploration becomes continuously attractive, establishing habitats on extraterrestrial planetary bodies is of particular interest for further deep-space investigations. Several space missions have emphasized the Moon, which is regarded as an outpost for developing sustainable ISRU programs, to pave the way for future Mars missions. High-temperature ISRU processes driven by concentrated solar energy have been recognized as a potential pathway to provide materials and power for long-term space explorations and construction on the lunar surface.

## 2. Methodology
### 2.1. Sintered ETC Modeling
The proposed ETC model is built on previous models for bi-sized sintered ceramic powders, improved for multi-sized particle systems. The model uses shape factors to characterize the irregular geometry of regolith particles and considers solid, gas, and radiation conductivity components.

### 2.2. Baseline Parameters
| Physical properties (unit) | Value |
| :--- | :--- |
| Radius of small particle (µm) | 15 |
| Radius of medium particle (µm) | 47 |
| Radius of large particle (µm) | 94 |
| Material density, $\rho_m$ (kg/m³) | 3100 |
| Initial porosity, $\phi$ | 0.45 |
| Emissivity, $\epsilon$ | 0.925 |
| Sintering Temperature (°C) | 900–1150 |
| Holding time (min) | 60 |

## 3. Results and Validation
### 3.1. Specific Surface Area
The specific surface area decreases with increasing sintering temperature due to sintered neck growth. The model underestimated specific surface area with a mean error of 20.9% compared to experimental data.

### 3.2. Effective Thermal Conductivity
The ETC of all sintered samples was significantly enhanced by the sintering process, approximately 5-20 times higher than green samples. The RMSE of sintered samples with small particles was 13.2%, medium 12.1%, and large 13.7%.

## 4. Solar Sintering Application
A transient solar-sintered heat transfer numerical model was developed based on the Finite Volume Method (FVM). Coupling the ETC and heat transfer model allowed for iterative simulation of neck evolution and thermal conductivity updates during the heating process. The optimal arrangement of multi-layered regolith (placing fine particles at the top for higher surface energy and larger particles below for better ray penetration) improved sintered depth by 45%.

## 5. Conclusions
1. An analytical model of sintered LMS-1 thermal conductivity was developed considering neck resistance and irregular particle shapes.
2. The FVM coupled to the ETC model simulates the update of microstructure and temperature simultaneously, showing good agreement with measurements (RMSE=5.5%).
3. Sintering increases thermal conductivity significantly, and optimizing Particle Size Distribution (PSD) can greatly enhance sintering efficiency for lunar construction.