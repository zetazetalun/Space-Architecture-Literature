# Investigation into Measuring Low Levels of Cohesion of Regolith Simulants

**Authors:** Robert L. Worley II, Laura Obregon, Lane Feldeisen, Brandon Nimberger, Colin Palmer, and Mandar M. Dewoolkar

**Affiliation:** College of Engineering and Mathematical Sciences, Dept. of Civil and Environmental Engineering, Univ. of Vermont, Burlington, VT.

## ABSTRACT
Lunar and Martian regoliths are similar to terrestrial soils in that they appear granular but are expected to contain a small amount of cohesion. As such, cohesion in extraterrestrial regoliths pose challenges for future space operations such as in situ resource utilization (ISRU). As part of preparing for human or robotic missions, it would be necessary to perform geotechnical activities similar to those typical of resource extraction on Earth. ISRU requires a better understanding of mechanical properties of regoliths and to recreate those conditions for physical modeling on Earth. The specific goal of this study was to evaluate two methods—vertical cut and simple direct shear testing—and assess their efficacy in reliably measuring small amounts of cohesion in lunar simulants: JSC-1A and GRC-3. Findings indicate that vertical cut testing cohesion estimates for JSC-1A at relative densities 0%–80% ranged between 0.115 and 0.971 kPa and cohesion estimates for GRC-3 at relative densities 0%–80% ranged between 0.190 and 1.872 kPa. Additionally, results show vertical cut testing provides monotonically increasing cohesion estimates with increased relative density, but simple direct shear testing did not establish any particular trend in cohesion measurements.

## INTRODUCTION
Understanding the expected surface regoliths (soils) will influence humans’ ability to explore or inhabit extraterrestrial bodies. Reliable simulation of regolith properties is necessary for geotechnical aspects of space exploration such as landing, walking, and investigating potential utilization of lunar resources to develop extraterrestrial habitats (NASA, 2017).

Soil shear strength is expressed by the Mohr-Coulomb failure criterion:

$$\tau_f = \sigma \tan \phi + c$$ (Eq.1)

Where:
- $\tau_f$ is shear stress at failure
- $\sigma$ is normal stress on the failure plane
- $\phi$ is the internal friction angle
- $c$ is cohesion

## EXPERIMENTAL METHODS

### Materials
The study examined lunar simulants **JSC-1A** (similar to Apollo 14 mare basalt) and **GRC-3** (developed for vehicle terramechanics). Tests were conducted at relative densities ($D_r$) of 0, 20, 40, 60, and 80%.

**Table 1. General Material Properties of JSC-1A and GRC-3**

| Lunar Simulant | $D_{10}$ (mm) | $D_{30}$ (mm) | $D_{60}$ (mm) | $D_r$ (max) | $D_r$ (min) | USCS Classification | Internal Friction Angle $\phi$ (degrees) |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | 0.017 | 0.042 | 0.110 | 2.040 | 1.560 | SP-SM | 34.9-59.6 |
| GRC-3 | 0.021 | 0.075 | 0.210 | 1.939 | 1.520 | SM | 30.4-57.2 |

### Vertical Cut Test
This method determines cohesion based on the "critical height" ($H_c$) at which an unsupported vertical slope of soil fails. The cohesion is estimated as:

$$c = \frac{1}{2} \gamma H_c$$ (Eq.2)

Where $\gamma$ is the unit weight of soil.

### Simple Direct Shear Test
Shear stress at failure was computed as the maximum shear load divided by the specimen cross-sectional area:

$$\tau_f = \frac{F}{A_{cs}}$$ (Eq.3)

**Table 2. Dry Densities of Lunar Simulants JSC-1A and GRC-3**

| Relative Density (%) | JSC-1A ($g/cm^3$) | GRC-3 ($g/cm^3$) |
| :--- | :--- | :--- |
| 0 | 1.560 | 1.520 |
| 20 | 1.637 | 1.589 |
| 40 | 1.722 | 1.664 |
| 60 | 1.816 | 1.746 |
| 80 | 1.922 | 1.838 |
| 100 | 2.040 | 1.939 |

## RESULTS AND DISCUSSION

**Table 3. Vertical cut testing critical heights ($H_c$ in cm)**

| Simulant | Trial | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | Average | 1.47 | 2.17 | 3.37 | 4.90 | 10.10 |
| GRC-3 | Average | 2.50 | 2.80 | 3.80 | 8.63 | 20.37 |

**Table 4. Cohesion estimates (kPa) from vertical cut and simple direct shear**

| Simulant | Test Type | 0% $D_r$ | 20% $D_r$ | 40% $D_r$ | 60% $D_r$ | 80% $D_r$ |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| JSC-1A | Vertical Cut | 0.115 | 0.178 | 0.290 | 0.445 | 0.971 |
| JSC-1A | Simple Direct | 0.396 | 0.722 | 0.413 | 0.546 | 0.582 |
| GRC-3 | Vertical Cut | 0.190 | 0.222 | 0.316 | 0.753 | 1.872 |
| GRC-3 | Simple Direct | 0.214 | 0.282 | 0.169 | 0.174 | 0.463 |

## CONCLUSIONS
Vertical cut testing proved to be a more reliable procedure for estimating low levels of cohesion in dry granular terrestrial soils used as lunar regolith simulants. Cohesion values for both JSC-1A and GRC-3 increased with relative density, supporting the hypothesis that regolith cohesion is primarily derived from the mechanical interlocking of irregular, angular particles.