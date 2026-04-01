# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck

## Abstract
Future space habitat structures must protect occupants and provide usable space in extreme environments. Due to high transportation costs, research focuses on Earth-independent designs using local regolith-based materials. This study explores spherical regolith-based concrete shells reinforced with carbon fiber polymer. A multi-objective optimization approach (Pareto optimization) is used to minimize transportation and construction costs while minimizing loss probability from radiation and micrometeorites. Results suggest that ISRU-based reinforced concrete is a valuable future investment for Lunar and potentially Mars settlements.

## Introduction
Human structures have evolved from using local materials (caves, igloos) to globally supplied materials (steel skyscrapers). Space exploration necessitates a return to local resource dependency due to the extreme cost of Earth-to-orbit transport. This research investigates reinforced concrete shells in five figures of merit compared to a baseline aluminum shell.

## Concepts and Materials
- **Lunar Concrete:** Exploiting lunar bases reduces fuel needs for take-off due to lower gravity. Infrastructure is required to protect against severe temperature cycles, vacuum effects, and radiation.
- **Radiation Shielding:** Absence of atmosphere and magnetic fields makes radiation (Solar Particle Events and Galactic Cosmic Rays) a major threat. Regolith shelters are considered the most effective solution.
- **3D Printing:** Technologies like D-Shape, Contour Crafting, and robotic fabrication are cited as methods for building structures in situ using lunar dust/regolith.
- **Structural Typologies:** 
  - **Aluminum Shell:** Baseline based on International Space Station habitation modules.
  - **Reinforced Concrete Shell:** Spherical dome using regolith-based concrete with a carbon fiber reinforced polymer (CFRP) inner bladder to resist internal pressure.

### Table 1: Material properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
Each spherical geometry is defined by: 
1. **Interior Radius (X1):** Defines the overall size.
2. **Tensile Layer Thickness (X2):** Effective thickness of reinforcement.
3. **Concrete Layer Thickness (X3):** Depth of regolith material.

**Evaluation Objectives:**
- Pressurized Volume
- Terrestrial Material Mass (minimization)
- Lunar Material Mass (minimization/proxy for complexity)
- Impact Protection (micrometeoroids)
- Radiation Protection

## Results and Discussion
- **Payload Reduction:** Maximum payload from Earth is reduced when using CFRP instead of aluminum due to higher strength-to-weight ratios.
- **Protection:** Reinforced concrete significantly increases micrometeoroid and radiation protection. While aluminum habitats are limited to ~7.5 cSv dose, concrete reduces this to ~5.8 cSv at 0.3m thickness.
- **Pareto Optimal Solutions:** Concrete cases satisfy multiple performance goals (volume, dose limits, impact resistance) where aluminum cases often fail to meet all criteria simultaneously.

### Table 2: Possible habitat configurations
| Variable/Objective | Aluminum | Concrete | Unit |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (from Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Meteoroid (Mass limit)| 2.94e-6 | 1.04e-5 | kg |
| Dose (Radiation) | 15.3 | 9.7 | cSv |

## Conclusion
Reinforced concrete should be investigated further as it enables larger volume habitats with superior protection and reduced Earth-launched mass. Multi-objective optimization helps decision-makers navigate the trade-offs between protection levels and logistical costs.