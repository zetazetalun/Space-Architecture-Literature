# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

**Journal:** International Journal of Heat and Mass Transfer 214 (2023) 124387  
**Authors:** Yuankun Zhang, Matthew Shaw, Geoffrey Brooks, Muhammad Akbar Rhamdhani, Chunsheng Guo, Zhuosheng Han, Thomas Jackson, Gregory Judkins

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The presented model was experimentally validated by the measured ETC and specific surface area of fabricated lunar simulant samples LMS-1 with various granularities sintered under air, argon gas and low vacuum (10⁻³ Pa). The simulated temperature profiles at the steady state concur well with measured data obtained from the solar sinter testing with an average Root Mean Squared Error (RMSE) of 5.5%, which performs better than the un-sintered ETC model (RMSE=12.7%). The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
High-temperature ISRU processes driven by concentrated solar energy have been recognized as a potential pathway to provide materials and power for long-term space explorations and construction on the lunar surface. Advantages include sufficient energy supply without atmospheric shielding, clean/renewable energy, and reduced transportation costs from Earth by using local regolith.

## 2. Experimental Data and Modeling Parameters

### Table 1: Chemical compositions (wt.%) of selected lunar samples and simulants.
| Sample | SiO2 | Al2O3 | CaO | MgO | FeO/Fe2O3 | TiO2 | Na2O | K2O | Others |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Apollo | 45.3 | 17.2 | 11.9 | 9.0 | 12.1 | 3.1 | 0.5 | 0.6 | 0.7 |
| Luna | 43.6 | 16.7 | 13.3 | 9.3 | 14.5 | 1.8 | 0.4 | 0.1 | 0.4 |
| LMS-1 | 46.9 | 12.4 | 7.0 | 16.8 | 8.6 | 3.6 | 1.7 | 0.7 | 1.3 |

### Table 2: Baseline parameters used for ETC modeling.
| Physical properties (unit) | Value |
| :--- | :--- |
| Radius of small particle (µm) | 15 |
| Radius of medium particle (µm) | 47 |
| Radius of large particle (µm) | 94 |
| Volume fraction, VS/M/L | 0.1/0.7/0.2 |
| Material density, ρm (kg/m³) | 3100 |
| Initial porosity, ϕ | 0.45 |
| Emissivity, ε | 0.925 |
| Sintering Temperature (°C) | 900–1150 |
| Holding time (min) | 60 |

## 3. Results
- **ETC Enhancement:** The ETC of all sintered samples was significantly enhanced by the sintering process, approximately 5-20 times higher than that of green (un-sintered) samples.
- **Sintering Depth:** Measured sintered depth improved by 45% by using an optimized multi-layered Particle Size Distribution (PSD) where medium and small particles are arranged at the top and second layers to facilitate ray penetration and sintering, while large particles at the bottom provide insulation.
- **Model Accuracy:** The mechanistic model achieved an average RMSE of 5.5% for temperature profile prediction compared to 12.7% for un-sintered models.

## 5. Conclusions
1. A mechanistic model for sintered LMS-1 thermal conductivity was developed considering neck resistance and irregular particle shapes.
2. Sintered samples under different atmospheres (air, argon, vacuum) show similar ETC values (RMSE < 5.2%).
3. The FVM model coupled with ETC effectively simulates the solar sintering process, allowing for the optimization of material layers to maximize sintering depth and efficiency.