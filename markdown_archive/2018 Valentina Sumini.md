# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Publication:** Earth and Space 2018, ASCE

## Abstract
The requirements of future space habitat structures are defined by their ability to protect occupants in extreme environments. Due to high transportation costs, research focuses on Earth-independent designs using local regolith-based materials. This study applies multiobjective optimization to spherical regolith-based concrete shells with carbon fiber polymer (CFRP) reinforcement. Objectives include minimizing transportation/construction costs and minimizing probability of loss due to radiation and micrometeoroids. Results indicate ISRU-based reinforced concrete is a valuable investment for lunar and Martian settlements.

## Introduction
Design for the lunar surface must address severe temperature cycles, structural fatigue, low-temperature brittle fractures, out-gassing, and vacuum effects. Radiation on the Moon (GCR and solar flares) is significantly higher than on Earth, making regolith shelters a primary solution.

## Lunar Habitats: Concepts and Materials
- **Lunar Concrete:** Utilizes Moon bases and reduced gravity to make colonization more appealing.
- **Construction Techniques:** Mention of Foster + Partners (inflatable/regolith), D-Shape technology (Enrico Dini), and Contour Crafting (Behrokh Khoshnevis).
- **Materials:** The study compares a baseline aluminum shell (ISS module type) with a reinforced concrete shell (regolith concrete with inner bladder and CFRP reinforcement).

### Table 1: Material properties
| Property | Units | Value |
|---|---|---|
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
The optimization uses five objectives:
1. **Pressurized Volume:** Maximized for crew/hardware.
2. **Terrestrial Material Mass:** Minimized to reduce launch costs.
3. **Lunar Material Mass:** Used as proxy for ISRU cost/complexity.
4. **Impact Protection:** Aiming for 0.993 Probability of No Penetration (PMP) over 5 years.
5. **Radiation Protection:** Minimizing annual dose equivalent from GCR.

## Results
- **Payload Reduction:** CFRP reinforcement reduces Earth-mass payload due to higher strength-to-density compared to aluminum.
- **Protection:** ISRU concrete habitats significantly increase protection against meteoroids and radiation.
- **Radiation Dose:** Aluminum minimum dose ~7.5 cSv; concrete (0.3m thickness) reduces dose to ~5.8 cSv.
- **Meteoroid Protection:** Concrete shells stop impactors orders of magnitude larger than aluminum can.

### Table 2: Possible habitat configurations
| Variable/Objective | Aluminum | Concrete | Units |
|---|---|---|---|
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload | 5435 | 3059 | kg |
| Concrete | 0 | 36283 | kg |
| Meteoroid | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Reinforced concrete shells enable designs that satisfy volume, mass, and protection goals simultaneously, whereas aluminum designs often fail to meet all safety/mass constraints in a single configuration.