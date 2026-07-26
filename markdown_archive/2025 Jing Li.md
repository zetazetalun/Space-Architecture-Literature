# Thermomechanical behavior of steel structural configurations subjected to cyclic cryogenic conditions in Martian environment

**Authors:** Jing Li, Yongtao Bai, Sifeng Bi, Michael Beer  
**Publication:** Advances in Space Research 76 (2025) 3700–3716  
**DOI:** 10.1016/j.asr.2025.06.069

## Abstract
Mars is a potential destination for future human colonization, and the construction of sustainable habitats capable of withstanding its extreme low-temperature fluctuations is critical. Numerical simulations are employed to assess the thermal and mechanical performance of three common extraterrestrial structural configurations — Arch, Dome, and Cylinder — under Martian diurnal temperature fluctuations. The study employs stainless steel as the primary material. Key focus areas include stress concentration, displacement, and fatigue failure in the structures.

## 1. Load Combinations
| Load Type | Application Position | Value | Notes |
| :--- | :--- | :--- | :--- |
| Gravitational Load | structure | $D_M = mg_M$ | $g_M = 3.73 m/s^2$ |
| Internal Pressure | Internal | 101.325 kPa | Standard Earth atmosphere for humans |
| Atmospheric Pressure | External | 900 Pa | Martian surface atmospheric pressure |
| Regolith shielding | External | $\rho_{RS} \cdot g_M \cdot h_{RS}$ | 3 m thickness |
| Thermal stress | Structure | $T_M$ | Diurnal cycle: -120 °C to +20 °C |

## 2. Materials and Methods
### 2.1. Material Properties (304L Stainless Steel)
- **Yield Stress:** 205 MPa
- **Young's Modulus:** 193 GPa (at 20 °C), 202 GPa (at -120 °C)
- **Density:** ~7.98 g/cm³

### 2.2. Regolith Properties
- **Density:** 1500 kg/m³
- **Thickness:** 3.0 m
- **Thermal Conductivity:** 0.036 W/m·K

## 3. Results and Discussion
### 3.1. Temperature Field Analysis
- **Unprotected Steel:** Diurnal fluctuations range from -105.2 °C to 13.5867 °C.
- **Protected Steel (3m Regolith):** The surface temperature of the steel structure stabilizes significantly. After 6870 thermal cycles, the surface temperature reaches a stable thermal equilibrium around -50 °C.

### 3.2. Structural Performance Comparison
| Configuration | Max Stress (Phase 1 - 687 cycles) | Max Stress (Phase 2 - with Shield) | Stress Reduction |
| :--- | :--- | :--- | :--- |
| Arch | 205 MPa | 205 MPa | 0% |
| Dome | 205 MPa | 148.4 MPa | 27.61% |
| Cylinder | 205 MPa | 10.35 MPa | 94.95% |

### 3.3. Failure Modes
- **Arch:** Cracks occur at the tips of the floor member (4 corners).
- **Dome:** Cracks initiate at the junction between the floor and dome member, extending upward.
- **Cylinder:** Cracks appear at the junction between the sidewall and floor member.
- **General:** Failure typically originates from the fixed bottom connections because expansion and contraction are constrained by the base plate.

## 4. Conclusion
1. **Regolith Shielding:** A 3-meter-thick layer is essential for mitigating thermal fluctuations and preventing rapid fatigue. 
2. **Optimal Geometry:** The **Dome** configuration is identified as optimal due to superior load distribution, spatial efficiency, and stiffness.
3. **Design Optimization:** Future designs should avoid sharp corners at floor-to-wall transitions and consider multi-layer flexible connections to alleviate thermal stress concentration.