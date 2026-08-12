# Investigation into Measuring Low Levels of Cohesion of Regolith Simulants

**Authors:** Robert L. Worley II, Laura Obregon, Lane Feldeisen, Brandon Nimberger, Colin Palmer, and Mandar M. Dewoolkar
**Affiliation:** College of Engineering and Mathematical Sciences, Dept. of Civil and Environmental Engineering, Univ. of Vermont, Burlington, VT
**Publication:** Earth and Space 2021, pp. 243-253, ASCE

## Abstract
Lunar and Martian regoliths appear granular but contain a small amount of cohesion, which poses challenges for ISRU and geotechnical activities. This study evaluates two methods—vertical cut and simple direct shear testing—to measure cohesion in lunar simulants JSC-1A and GRC-3. Vertical cut testing showed cohesion estimates for JSC-1A (0%–80% relative density) between 0.115 and 0.971 kPa, and for GRC-3 between 0.190 and 1.872 kPa. Vertical cut testing provided monotonically increasing cohesion estimates with density, whereas simple direct shear testing did not establish a clear trend.

## Introduction
Understanding regolith properties is vital for landing, walking, and developing extraterrestrial habitats. Soil shear strength is expressed via the Mohr-Coulomb failure criterion:

$$\tau_f = \sigma \tan \phi + c$$

Where $\tau_f$ is shear stress at failure, $\sigma$ is normal stress, $\phi$ is the internal friction angle, and $c$ is cohesion.

## Experimental Methods

### Materials
Two simulants were tested: 
- **JSC-1A:** Basaltic ash simulant matching Apollo 14 mare basalt properties.
- **GRC-3:** A lower-cost alternative developed for terramechanics testing.

**Table 1. General Material Properties**
| Lunar Simulant | $D_{10}$ (mm) | $D_{30}$ (mm) | $D_{60}$ (mm) | $D_r$ (max) | $D_r$ (min) | USCS | Friction Angle (°) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | 0.017 | 0.042 | 0.110 | 2.040 | 1.560 | SP-SM | 34.9-59.6 |
| GRC-3 | 0.021 | 0.075 | 0.210 | 1.939 | 1.520 | SM | 30.4-57.2 |

### Testing Methods
1.  **Vertical Cut Test:** Measures the "critical height" ($H_c$) at which an unsupported vertical slope fails. Cohesion is estimated as: $c = 0.5 \gamma H_c$.
2.  **Simple Direct Shear Test:** A modified version for small normal loads (0-10 kPa), allowing for the determination of the internal friction angle and cohesion through regression.

## Results and Discussion

**Table 3. Vertical Cut Testing Critical Heights (cm)**
| Simulant | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A (Avg) | 1.47 | 2.17 | 3.37 | 4.90 | 10.10 |
| GRC-3 (Avg) | 2.50 | 2.80 | 3.80 | 8.63 | 20.37 |

**Table 4. Cohesion Estimates (kPa)**
| Simulant | Test Type | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | Vertical Cut | 0.115 | 0.178 | 0.290 | 0.445 | 0.971 |
| JSC-1A | Simple Shear | 0.396 | 0.722 | 0.413 | 0.546 | 0.582 |
| GRC-3 | Vertical Cut | 0.190 | 0.222 | 0.316 | 0.753 | 1.872 |
| GRC-3 | Simple Shear | 0.214 | 0.282 | 0.169 | 0.174 | 0.463 |

## Conclusions
Vertical cut testing effectively estimates low-level cohesion in dry granular regolith simulants. The findings support the hypothesis that apparent cohesion in lunar regolith results from mechanical interlocking of irregular particles, as cohesion increased consistently with relative density.