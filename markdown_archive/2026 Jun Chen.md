# Mesoscale Mechanisms Governing the Shear Strength of Lunar Regolith: Effects of Low Confining Stress and Irregular Particle Morphology

**Authors:** Jun Chen, Ruilin Li, Yukun Ji, Pinqiang Mo  
**Journal:** Materials 2026, 19, 1439  
**Date:** April 2026  

## Abstract
Understanding the mechanical behavior of lunar regolith is critical for the success of future lunar excavation and construction missions. Irregular particle morphology and low geostatic stress are recognized as key factors contributing to the high internal friction angle of this unique extraterrestrial geomaterial. In this study, consolidated drained triaxial compression tests were performed on CUMT-1 lunar regolith simulant and Fujian standard sand. Complementary discrete element method (DEM) simulations were conducted to analyze mesoscopic responses. A robust macroscopic–mesoscopic strength correlation model was established to predict the normalized deviatoric stress of granular assemblies.

## 1. Introduction
The lunar regolith layer is a critical repository of mineral resources and forms the primary load-bearing foundation for future lunar bases. Its shear strength is primarily determined by relative density, particle size distribution, particle morphology, in situ stress, and single-particle strength. Low geostatic stress on the Moon contributes to an increase in the internal friction angle.

## 2. Material and Methods
### 2.1. Laboratory Triaxial Compression Test
- **CUMT-1 Lunar Regolith Simulant:** Developed for geotechnical use; components include volcanic ash and ferroferric oxide (Fe3O4). Produced via high-temperature sintering and impact crushing.
- **Fujian Standard Sand (FS):** Used as a control for more rounded terrestrial soils.

#### Table 1. Morphology quantification results.
| Particle Size (mm) | Simulant Aspect Ratio | Simulant Angularity | Simulant Texture | FS Aspect Ratio | FS Angularity | FS Texture |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| >2 | 0.726 | 0.0502 | 0.0195 | 0.743 | 0.0218 | 0.0083 |
| 1~2 | 0.697 | 0.0515 | 0.0184 | 0.741 | 0.0168 | 0.0072 |
| 0.5~1 | 0.728 | 0.0616 | 0.0190 | 0.822 | 0.0282 | 0.0081 |
| 0.25~0.5 | 0.739 | 0.0783 | 0.0187 | 0.753 | 0.0324 | 0.0086 |
| 0.1~0.25 | 0.701 | 0.0634 | 0.0181 | 0.762 | 0.0337 | 0.0098 |
| 0.05~0.1 | 0.712 | 0.0517 | 0.0179 | 0.687 | 0.0498 | 0.0103 |
| **Mean value** | **0.717** | **0.0600** | **0.0186** | **0.751** | **0.0305** | **0.0087** |

### 2.2. Discrete Element Method (DEM) Biaxial Compression
- **Software:** PFC 5.0.
- **Parameters:** Damping ratio 0.7, Initial porosity 0.06, Particle normal stiffness 7.5 x 10^7 N/m.
- **Confining Pressures:** 5, 10, 20, 30, 50, 100, and 150 kPa.

## 3. Results and Discussion
### 3.1. Triaxial Test Results
#### Table 3. Strength parameters in triaxial tests.
| Soil Type | σ3 (kPa) | φ_peak (°) | φ_residual (°) | θ (°) |
| :--- | :--- | :--- | :--- | :--- |
| CUMT-1 | 10 | 59.4 | 52.5 | 60.0 |
| CUMT-1 | 150 | 54.8 | 41.2 | 33.7 |
| FS | 10 | 54.9 | 51.8 | 50.4 |
| FS | 150 | 48.1 | 44.3 | 31.3 |

### 3.3. Macro-Mesoscopic Correlation
A linear model was established between normalized macroscopic strength and normalized mesoscopic strength:

$$\hat{\sigma}_d = 14.74 \hat{f}_{mes} - 1.5$$ (R² = 0.97)

## 4. Conclusions
1. A novel macro–mesoscopic strength correlation model was proposed using interparticle contact force and coordination number.
2. Both friction coefficient and angularity increases lead to higher peak friction angles.
3. Decreased confining pressure reduces coordination number but increases normalized interparticle contact force, causing peak friction angle to rise.