# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Most existing literature has been focused on the packed lunar regolith without considering the sintering mechanism. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The presented model was experimentally validated by the measured ETC and specific surface area of fabricated lunar simulant samples LMS-1 with various granularities sintered under air, argon gas and low vacuum (10^-3 Pa). Furthermore, the heat transfer process within solar sintered LMS-1 bed was simulated coupled with the ETC model. Transient behaviors of microstructure, thermal conductivity and temperature profile during solar heating were simulated iteratively. The simulated temperature profiles at the steady state concur well with measured data obtained from the solar sinter testing with an average Root Mean Squared Error (RMSE) of 5.5%, which performs better than the un-sintered ETC model (RMSE=12.7%). The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
As space exploration becomes continuously attractive, establishing habitats on extraterrestrial planetary bodies is of particular interest for further deep-space investigations. Several space missions have emphasized the Moon, which is regarded as an outpost for developing sustainable ISRU programs, to pave the way for future Mars missions. High-temperature ISRU processes driven by concentrated solar energy have been recognized as a potential pathway to provide materials and power for long-term space explorations and construction on the lunar surface.

## 2. Sintered ETC modeling
The proposed ETC model in the current study is built on the multi-sized particle system, considering coordination numbers, shape factors to characterize irregular geometry, and heat transfer pathways through solid particles, gas (air) in voids, and radiation. The evolution of neck growth between multi-sized particles was simulated using a Monte-Carlo based algorithm.

### Table 1: Chemical compositions (wt.%) of selected lunar samples and simulants
| Sample | SiO2 | Al2O3 | CaO | MgO | FeO/Fe2O3 | TiO2 | Na2O | K2O | Others |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Apollo | 45.3 | 17.2 | 11.9 | 9.0 | 12.1 | 3.1 | 0.5 | 0.6 | 0.7 |
| Luna | 43.6 | 16.7 | 13.3 | 9.3 | 14.5 | 1.8 | 0.4 | 0.1 | 0.4 |
| Simulant | 46.4 | 15.0 | 9.2 | 7.9 | 12.4 | 2.5 | 3.1 | 1.5 | 1.4 |
| LMS-1 | 46.9 | 12.4 | 7.0 | 16.8 | 8.6 | 3.6 | 1.7 | 0.7 | 1.3 |

### Table 2: Baseline parameters used for ETC modeling
| Physical properties (unit) | Value |
| :--- | :--- |
| Radius of small particle (μm) | 15 |
| Radius of medium particle (μm) | 47 |
| Radius of large particle (μm) | 94 |
| Volume fraction, VS/M/L | 0.1/0.7/0.2 |
| Material density, ρm (kg/m3) | 3100 |
| Initial porosity, ϕ | 0.45 |
| Emissivity, ε | 0.925 |
| Temperature (°C) | 900–1150 |
| Holding time (min) | 60 |

## 3. Experimental validation of ETC
LMS-1 samples were fabricated under air, argon, and vacuum. ETC was measured using the HotDisk TPS 2500 system. Results showed that the sintering process significantly enhanced ETC (5-20 times higher than green samples). The model achieved a high accuracy with an average RMSE of 5.5% at steady state.

## 4. Heat transfer in solar-sintered lunar regolith
A transient heat transfer numerical model based on the Finite Volume Method (FVM) was developed. Experiments using high-flux solar simulators (HFSS) with metal-halide lamps validated that optimizing the particle size distribution—placing smaller particles at the surface to encourage sintering and larger particles at the base for insulation—improved sintering depth by 45%.

## 5. Conclusions
1. An analytical model of sintered LMS-1 thermal conductivity was developed and validated with a 20.9% mean error in specific surface area and high accuracy in ETC across different atmospheres.
2. The FVM-coupled ETC model successfully simulates solar sintering processes, accurately predicting temperature profiles (RMSE=5.5%).
3. Sintered depth can be significantly optimized through controlled particle size distribution, enhancing the efficiency of lunar ISRU construction.