# Effect of Low-Temperature Fluctuations on Martian Steel Structures: Numerical and Analytical Studies

**Authors:** Yongtao Bai, Jing Li, and Xuhong Zhou  
**Journal:** Journal of Cold Regions Engineering (ASCE)  
**Publication Date:** January 27, 2025  
**DOI:** 10.1061/JCRGEI.CRENG-875

## Abstract
To harness a variety of unique resources, humanity is progressively venturing deeper into space. This endeavor necessitates a comprehensive investigation into the formidable challenges presented by hostile environments, particularly the impact of extreme low-temperature fluctuations on extraterrestrial engineering and construction. This paper employs numerical simulation methodologies to scrutinize the displacement variations and stress distribution within a full-scale circular arch steel structure subjected to diverse thermal cycles. The findings offer an empirical foundation for the architectural design and material selection pertinent to the establishment of a Martian base.

## Introduction
Mars is deemed the most viable candidate for interplanetary colonization. However, its environment presents extremities such as reduced gravity and extreme temperature fluctuations. The thin atmosphere results in a great temperature difference between day and night (-110°C to +20°C). This study investigates the fatigue performance of steel structures under these alternating low temperatures using ABAQUS finite-element analysis.

### Material Selection
Steel is highlighted for its low cost, easy processing, and excellent low-temperature resistance compared to titanium or aluminum. Crucially, the availability of iron and nickel on Mars in elemental form supports the feasibility of in-situ resource utilization (ISRU) for steel production.

## Overview of the Martian Environment
### Low-Temperature Alternating Environment
- **Diurnal Cycle:** ~24 h, 39 min.
- **Temperature Range:** Max +20°C, Min -110°C.
- **Simulation Cycle:** 24 h cycle with 16 h cooling and 8 h warming phases (triangular wave).

## Structure Form and Loadings
- **Concept:** Semicircular arch steel member with a flat floor member.
- **Dimensions:** Radius 5 m, Thickness 50 mm, Longitudinal span 10 m.
- **Gravitational Acceleration (gM):** 3.73 m/s².
- **Internal Pressure:** 101.325 kPa (1 atm).
- **External Pressure (Regolith):** 18.687 kPa (assumes 3 m regolith shielding).

### Table 2: Material Parameters (Steel)
| Parameter | Value |
| :--- | :--- |
| Density (kg/m³) | 7,850 |
| Conductivity (W/m·°C) | 54 |
| Specific Heat (J/kg·°C) | 425 |
| Expansion Coefficient (1/°C) | 1.36 × 10⁻⁵ |
| Yield Stress (MPa) | 250 |
| Young’s Modulus (MPa) | 2.06 × 10⁵ |
| Poisson's Ratio | 0.3 |

## Results and Discussion
- **Structural Integrity:** After simulating 1–10 Martian years (up to 6,870 cycles), no cracking or failure was observed. The structure remains within safety parameters.
- **Stress Distribution:** Without thermal cycles, stress is localized on the arch. With thermal cycling, stress concentration shifts to the floor member and the juncture between the arch and floor.
- **Displacement:** Without cycles, apex displacement is ~2.7 mm. Under cyclic loading, peak displacement fluctuates between 12.16 mm and 13.11 mm.

## Conclusion and Recommendations
1. The 50-mm-thick steel arch is capable of meeting Martian environmental requirements for 10 years.
2. **Design Recommendation:** Architectural designs should thicken the floor member to improve bearing capacity and optimize the arch-floor connection to mitigate stress concentration.
3. Displacement follows a cyclical pattern rather than a monotonic increase, indicating the material reaches an equilibrium between stress and deformation after initial cycles.