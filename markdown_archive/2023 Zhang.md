# Investigation of heat transfer processes in multi-sized solar-sintered regolith for lunar ISRU program

**Journal:** International Journal of Heat and Mass Transfer  
**Volume/Issue:** 214 (2023) 124387  
**Authors:** Yuankun Zhang, Matthew Shaw, Geoffrey Brooks, Muhammad Akbar Rhamdhani, Chunsheng Guo, Zhuosheng Han, Thomas Jackson, Gregory Judkins  

## Abstract
Effective Thermal Conductivity (ETC) prediction of sintered lunar regolith plays a crucial role in developing extraterrestrial thermal processing and construction techniques for In-situ Resource Utilization (ISRU) projects on the Moon. Most existing literature has been focused on the packed lunar regolith without considering the sintering mechanism. Herein, we presented a mechanistic model to estimate the ETC of sintered lunar regolith. The Monte-Carlo method was applied to simulate the thermal neck resistance between multi-scaled particles, while the irregular particle geometry was characterized by shape factors. The presented model was experimentally validated by the measured ETC and specific surface area of fabricated lunar simulant samples LMS-1 with various granularities sintered under air, argon gas and low vacuum (10⁻³ Pa). Furthermore, the heat transfer process within solar sintered LMS-1 bed was simulated coupled with the ETC model. Transient behaviors of microstructure, thermal conductivity and temperature profile during solar heating were simulated iteratively. The simulated temperature profiles at the steady state concur well with measured data obtained from the solar sinter testing with an average Root Mean Squared Error (RMSE) of 5.5%, which performs better than the un-sintered ETC model (RMSE=12.7%). The measured sintered depth was improved by 45% with an optimized particle size distribution (PSD) arrangement.

## 1. Introduction
High-temperature ISRU processes driven by concentrated solar energy provide a pathway for long-term space exploration and construction on the lunar surface. Advantages include: 1) sufficient energy supply without atmosphere shielding; 2) clean and renewable; 3) easing transportation costs by using local regolith feedstocks.

## 2. Methodology
- **Mechanistic Model:** Estimates ETC of sintered regolith using Monte-Carlo simulations for thermal neck resistance.
- **Simulants:** Lunar regolith simulant LMS-1 (Exolith Lab) used to represent lunar mare soil.
- **Sintering Modeling:** Incorporates coordination number, solid particle conduction, initial contact area (JKR model), and shape factors (sphericity/roundness).
- **Radiation Conductivity:** Modeled using sphere packing bed approximated as serially connected slabs.

## 3. Results & Discussion
### Table 1: Chemical compositions (wt.%) of selected lunar samples and simulants.
| Sample | SiO2 | Al2O3 | CaO | MgO | FeO/Fe2O3 | TiO2 | Na2O | K2O | Others |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Apollo | 45.3 | 17.2 | 11.9 | 9.0 | 12.1 | 3.1 | 0.5 | 0.6 | 0.7 |
| Luna | 43.6 | 16.7 | 13.3 | 9.3 | 14.5 | 1.8 | 0.4 | 0.1 | 0.4 |
| LMS-1 | 46.9 | 12.4 | 7.0 | 16.8 | 8.6 | 3.6 | 1.7 | 0.7 | 1.3 |

### Table 2: Baseline parameters used for ETC modeling.
| Physical properties (unit) | Value |
| :--- | :--- |
| Radius of small particle (μm) | 15 |
| Radius of medium particle (μm) | 47 |
| Radius of large particle (μm) | 94 |
| Initial porosity | 0.45 |
| Material density (kg/m³) | 3100 |
| Emissivity | 0.925 |

## 5. Conclusions
1. An analytical model of sintered LMS-1 thermal conductivity was developed considering neck resistance and irregular shapes, with a mean error of 20.9% for surface area validation.
2. The FVM model coupled with ETC predicted steady-state temperature profiles with an average RMSE of 5.5%.
3. Optimizing the particle size distribution (PSD) arrangement (layering smaller particles on top of larger ones) increased the sintering depth by 45% compared to original PSD.