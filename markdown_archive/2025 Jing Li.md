# Thermomechanical behavior of steel structural configurations subjected to cyclic cryogenic conditions in Martian environment

**Authors:** Jing Li, Yongtao Bai, Sifeng Bi, Michael Beer
**Journal:** Advances in Space Research 76 (2025) 3700–3716
**DOI:** https://doi.org/10.1016/j.asr.2025.06.069

## Abstract
Mars is a potential destination for future human colonization, and the construction of sustainable habitats capable of withstanding its extreme low-temperature fluctuations is critical. Numerical simulations are employed to assess the thermal and mechanical performance of three common extraterrestrial structural configurations — Arch, Dome, and Cylinder — under Martian diurnal temperature fluctuations. The study employs stainless steel as the primary material. Key focus areas include stress concentration, displacement, and fatigue failure in the structures.

## 1. Introduction
Mars surface conditions are characterized by severe diurnal temperature fluctuations (ΔT > 100 °C) and low atmospheric pressure (~0.6 kPa). The first-ever successful application of stainless steel in Starship’s hull validates its engineering feasibility in deep-space extreme environments. This study conducts a comparative analysis of the thermal response and fatigue behavior of Arch, Dome, and Cylinder configurations under Martian cryogenic thermal cycling.

## 2. Load Combinations and Structural Configurations

### 2.1. Load Combinations
Martian structures face vastly different environmental conditions compared to terrestrial structures. Key loads analyzed include:
1. **Gravity load:** 3.73 m/s².
2. **External atmospheric pressure:** ~0.61 kPa to 0.9 kPa.
3. **Internal pressure:** 101.325 kPa (Earth-like living conditions).
4. **Regolith shielding:** 3 meters of regolith for protection against radiation and thermal fluctuations.

### Table 1: Load combinations for Martian habitat structures
| Load Type | Application Position | Value | Notes |
| :--- | :--- | :--- | :--- |
| Gravitational Load | structure | DM = mgM | gM = 3.73 m/s² |
| Internal Pressure | Internal | 101.325 kPa | For human suitability |
| Atmospheric Pressure | External | 900 Pa | Martian surface pressure |
| Regolith shielding | External | =ρRS·gM·hRS | 3 m thickness |
| Thermal stress | Structure | TM | Based on ΔT |

## 3. Materials and Methods
- **Primary Material:** 304L stainless steel (thickness: 100 mm).
- **Shielding:** 3m Martian regolith.
- **Software:** ABAQUS (finite element method) using sequential thermodynamic coupling.
- **Configurations:** Arch, Dome, and Cylinder (5m diameter, 10m depth/segments).

### Table 2: Physical parameters of 304L steel
| Property | Value (at 20°C) |
| :--- | :--- |
| Density | 7.98 g/cm³ |
| Yield stress | 205 MPa |
| Young’s modulus | 193 GPa |
| Poisson’s ratio | 0.3 |

## 4. Results and Discussion
### 4.1. Thermal Performance
- **Phase 1 (Bare):** Structure surface fluctuates between -105.2 °C and 13.5 °C.
- **Phase 2 (Regolith Shielded):** 3m of regolith stabilizes the steel structure surface temperature to approximately 0.69 °C after 687 cycles.
- **Thermal Equilibrium:** Structures gradually reach a stable thermal state. A relationship was established: $T_{min} = 73.327 \times e^{-c/1488.945} - 50.956$.

### 4.2. Structural Comparison
- **Failure Modes:** Failure typically originates at the fixed base plate/bottom connections due to constrained thermal expansion/contraction.
- **Stress Reduction:** Regolith shielding reduced maximum stress by 0% (Arch), 27.61% (Dome), and 94.95% (Cylinder) compared to unshielded phases.
- **Displacement:** The Dome showed the highest stiffness and lowest displacement (1.665 mm shielded) compared to the Cylinder (2.180 mm shielded).

## 5. Conclusions
1. Regolith shielding (3m) is highly effective in mitigating thermal fatigue, especially for the Cylinder configuration.
2. The Dome configuration is optimal for Martian habitats due to superior load distribution and stability.
3. Structural optimization should focus on base connections and transition areas to reduce stress concentrations.