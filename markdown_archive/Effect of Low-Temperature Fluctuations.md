# Effect of Low-Temperature Fluctuations on Martian Steel Structures: Numerical and Analytical Studies

**Authors:** Yongtao Bai, Jing Li, and Xuhong Zhou  
**Journal:** Journal of Cold Regions Engineering (ASCE)  
**Date:** Published online January 27, 2025  
**DOI:** 10.1061/JCRGEI.CRENG-875

## Abstract
To harness a variety of unique resources, humanity is progressively venturing deeper into space. This endeavor necessitates a comprehensive investigation into the formidable challenges presented by hostile environments, particularly the impact of extreme low-temperature fluctuations on extraterrestrial engineering and construction. This paper employs numerical simulation methodologies to scrutinize the displacement variations and stress distribution within a full-scale circular arch steel structure subjected to diverse thermal cycles, thereby assessing the influence of severe cryogenic temperature fluctuations on Martian steel infrastructure. The findings of this research contribute to understanding the resilience of such structures within fluctuating low-temperature conditions, thereby offering an empirical foundation for the architectural design and material selection pertinent to the establishment of a Martian base.

## 1. Introduction
Mars is considered a primary candidate for human migration due to its gravitational pull and atmospheric composition. A critical challenge for Martian outposts is the selection of construction materials. Steel is highlighted due to its low cost, easy processing, recyclability, and excellent low-temperature resistance compared to other materials. Most importantly, the availability of iron and nickel on Mars allows for potential in situ resource utilization (ISRU), making steel production potentially less energy-intensive than on Earth.

## 2. Overview of the Martian Environment
### Low-Temperature Alternating Environment
Martian diurnal cycles (sols) last 24h 39min. Due to the thin atmosphere, temperature fluctuations are extreme. Simulations in this study use a maximum of +20°C and a minimum of -110°C, following a 24-hour cycle (16h cooling, 8h warming) modeled as a triangular wave.

## 3. Structural Design and Loading
### Habitat Specifications
- **Form:** Semicircular arch steel member with a flat floor.
- **Radius:** 5 m.
- **Thickness:** 50 mm.
- **Span:** 10 m.
- **Capacity:** Designed for four astronauts per NASA specifications (93 m²).

### Loading Conditions
- **Gravity:** 3.73 m/s² (Martian gravity).
- **Internal Pressure:** 101.325 kPa (1 atm, Earth equivalent).
- **External Pressure:** 18.687 kPa (representing a 3m regolith shielding layer).
- **Wind/Seismic:** Considered negligible compared to internal pressure.

## 4. Numerical Simulation (ABAQUS)
The study uses sequential thermal coupling in ABAQUS to simulate up to 10 Martian years (6,870 cycles). 

### Material Parameters (Steel)
| Parameter | Value |
| :--- | :--- |
| Density | 7,850 kg/m³ |
| Conductivity | 54 W/m·°C |
| Specific Heat | 425 J/kg·°C |
| Expansion Coefficient | 1.36 × 10⁻⁵ /°C |
| Yield Stress | 250 MPa |
| Young's Modulus | 2.06 × 10⁵ MPa |
| Poisson's Ratio | 0.3 |

## 5. Results and Discussion
- **Structural Integrity:** No cracking or failure occurred over the simulated 1-10 Martian years.
- **Stress Distribution:** Without thermal cycling, stress is localized on the arch. With thermal cycling, stress concentration shifts significantly to the floor-to-arch connection.
- **Displacement:** In a simple stress field (no thermal cycles), the apex displacement was 2.70406 mm. Under thermal fluctuations, displacement becomes cyclical, reaching peaks between 12.16 and 13.11 mm.
- **Fatigue:** Thermal cycling causes material fatigue, reducing stiffness and strength, leading to fluctuations in the stress-time curves.

## 6. Conclusions
1. A 50-mm steel arch structure can survive the Martian thermal environment for at least 10 Martian years without structural failure.
2. Designers should thicken the floor member and optimize the arch-to-floor connection to manage stress concentration.
3. The displacement of the habitat vault follows a cyclical pattern dictated by thermal expansion and contraction, rather than a linear trend.
