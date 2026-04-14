# Investigation into Measuring Low Levels of Cohesion of Regolith Simulants

**Authors:** Robert L. Worley II, Laura Obregon, Lane Feldeisen, Brandon Nimberger, Colin Palmer, and Mandar M. Dewoolkar  
**Publication:** Earth and Space 2021, ASCE

## Abstract
Lunar and Martian regoliths are similar to terrestrial soils in that they appear granular but are expected to contain a small amount of cohesion. Cohesion in extraterrestrial regoliths poses challenges for future space operations such as in situ resource utilization (ISRU). This study evaluates two methods—vertical cut and simple direct shear testing—to reliably measure small amounts of cohesion in lunar simulants: JSC-1A and GRC-3. Results indicate that vertical cut testing provides monotonically increasing cohesion estimates with increased relative density, whereas simple direct shear testing did not establish a clear trend.

## Introduction
Understanding surface regolith properties is critical for landing, walking, and utilizing lunar resources for habitat development. Soil shear strength is expressed by the Mohr-Coulomb failure criterion:

$$\tau_f = \sigma \tan \phi + c$$

Where $\tau_f$ is shear stress at failure, $\sigma$ is normal stress, $\phi$ is the internal friction angle, and $c$ is cohesion. Lunar regolith cohesion is estimated at 0.1–1.0 kPa based on Apollo data.

## Experimental Methods

### Materials
The study used two simulants:
- **JSC-1A:** Similar to Apollo 14 mare basalt (glass-rich basaltic ash).
- **GRC-3:** Developed for vehicle terramechanics; cheaper but less compositionally accurate than JSC-1A.

**Table 1. General Material Properties of JSC-1A and GRC-3**
| Lunar Simulant | $D_{10}$ (mm) | $D_{30}$ (mm) | $D_{60}$ (mm) | $D_r$ (max) | $D_r$ (min) | USCS Classification | Internal Friction Angle $\phi$ (degrees) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | 0.017 | 0.042 | 0.110 | 2.040 | 1.560 | SP-SM | 34.9-59.6 |
| GRC-3 | 0.021 | 0.075 | 0.210 | 1.939 | 1.520 | SM | 30.4-57.2 |

### Testing Procedures
1. **Vertical Cut Test:** Measures cohesion based on the "critical height" ($H_c$) at which an unsupported vertical slope fails. Estimated cohesion $c = 0.5 \gamma H_c$.
2. **Simple Direct Shear Test:** A modified direct shear test allowing for small normal loads (0–10 kPa).

**Table 2. Dry Densities of Lunar Simulants JSC-1A and GRC-3**
| Relative Density (%) | JSC-1A ($g/cm^3$) | GRC-3 ($g/cm^3$) |
| :--- | :--- | :--- |
| 0 | 1.560 | 1.520 |
| 20 | 1.637 | 1.589 |
| 40 | 1.722 | 1.664 |
| 60 | 1.816 | 1.746 |
| 80 | 1.922 | 1.838 |
| 100 | 2.040 | 1.939 |

## Results and Discussion

**Table 3. Vertical cut testing critical heights of JSC-1A and GRC-3**
| Lunar Simulant | Trial | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **JSC-1A** (cm) | Average | 1.47 | 2.17 | 3.37 | 4.90 | 10.10 |
| **GRC-3** (cm) | Average | 2.50 | 2.80 | 3.80 | 8.63 | 20.37 |

**Table 4. Cohesion estimates from vertical cut and simple direct shear testing**
| Simulant | Test Type | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| **JSC-1A** | Vertical Cut (kPa) | 0.115 | 0.178 | 0.290 | 0.445 | 0.971 |
| | Simple Direct (kPa) | 0.396 | 0.722 | 0.413 | 0.546 | 0.582 |
| **GRC-3** | Vertical Cut (kPa) | 0.190 | 0.222 | 0.316 | 0.753 | 1.872 |
| | Simple Direct (kPa) | 0.214 | 0.282 | 0.169 | 0.174 | 0.463 |

## Conclusions
Vertical cut testing proved to be more effective for measuring the low levels of cohesion expected in dry granular regolith. The cohesion of both simulants increased with relative density, supporting the hypothesis that apparent cohesion in lunar regolith stems from mechanical interlocking of irregular, angular particles.