# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Published in:** Earth and Space 2018 (ASCE)

## Abstract
Future space habitat requirements include protecting occupants in extreme environments while providing usable space. Due to high transportation costs, research focuses on Earth-independent designs using local regolith-based materials. This study uses multi-objective optimization to evaluate spherical regolith-based concrete shells reinforced with carbon fiber polymer (CFRP). Objectives include minimizing transportation/construction costs and minimizing the probability of loss due to radiation and micrometeorites. Results indicate ISRU-based reinforced concrete is a valuable future investment for Lunar and Martian settlements.

## Introduction
Habitat design is driven by resource availability, transportation capacity, and environmental protection. For lunar habitats, a regolith shelter is considered the most meaningful solution to protect against solar winds, flares, and Galactic Cosmic Rays (GCR). Previous concepts include Foster + Partners' inflatable/regolith combination and D-Shape or Contour Crafting 3D printing technologies.

## Methodology
The study compares two primary typologies:
1.  **Aluminum Shell:** Based on ISS habitation modules.
2.  **Reinforced Concrete Shell:** Spherical dome using lunar regolith-based concrete with internal CFRP reinforcement and an airtight inner bladder.

### Material Properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

### Design Variables
*   **X_1:** Interior Radius (m)
*   **X_2:** Tensile Layer Thickness (m)
*   **X_3:** Concrete Layer Thickness (m)

### Objectives
1.  Maximize Pressurized Volume
2.  Minimize Terrestrial Material Mass
3.  Minimize Lunar Material Mass
4.  Minimize Impact Vulnerability (Micrometeoroids)
5.  Minimize Radiation Dose (GCR)

## Results
The multi-objective Pareto optimization revealed that reinforced concrete significantly outperforms aluminum in protection metrics. For a similar interior volume, concrete shells reduced the GCR dose to 9.7 cSv compared to 15.3 cSv for aluminum. Furthermore, concrete habitats can stop meteoroids with masses orders of magnitude greater than aluminum shells of equivalent volume.

| Configuration | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Meteoroid Limit | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Reinforced concrete is a valuable material for lunar habitats. Pareto optimization allows designers to understand trade-offs without prior weighting of objectives, showing that ISRU-based designs can meet performance goals (volume, protection, mass) that are impossible for single-lander aluminum designs.