# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck**

## Abstract
Future space habitat structures must protect occupants in extreme, isolated environments. Due to high transportation costs, research focuses on Earth-independent designs using local regolith-based materials. This study investigates spherical regolith-based concrete shells reinforced with carbon fiber polymers. A multi-objective optimization (Pareto optimization) is used to minimize transportation/construction costs while maximizing protection against radiation and micrometeorites. Results indicate that ISRU-based reinforced concrete is a superior solution compared to traditional aluminum shells for meeting safety and volume requirements.

## Introduction
Resource availability and transportation capacity have historically driven human structural design. For space, Earth-independent structural designs using local regolith are seen as a solution for long-term sustainability. This research compares reinforced concrete shells against baseline aluminum cases.

## Concepts and Materials
*   **Lunar Concrete:** Exploiting lunar bases reduces fuel needs for take-off due to lower gravity. Structures must withstand severe temperature cycles and radiation.
*   **Regolith Shelter:** Necessary for protection against solar wind, solar flares, and Galactic Cosmic Rays (GCR).
*   **Reinforcement:** Carbon fiber reinforced polymers (CFRP) are considered to handle tension stresses and increase performance against micrometeorite impacts.

### Material Properties

| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology
The study evaluates feasible geometries based on five objectives:
1.  **Pressurized Volume:** Maximizing usable space.
2.  **Terrestrial Material Mass:** Minimizing mass brought from Earth.
3.  **Lunar Material Mass:** Measuring the cost of processing local regolith.
4.  **Impact Protection:** Achieving a 0.993 Probability of No Penetration (PMP) over 5 years.
5.  **Radiation Protection:** Minimizing the Radiation Dose Equivalent.

## Results and Discussion
*   **GCR Dose:** Minimum dose in aluminum habitats is ~7.5 cSv, whereas concrete cases (0.3m thickness) can reduce this to ~5.8 cSv.
*   **Meteoroid Protection:** Reinforced concrete is significantly better at stopping hyper-velocity impacts compared to aluminum.
*   **Optimization:** In the aluminum baseline, it was not possible to satisfy all performance goals (volume, mass, protection) simultaneously. The concrete shell provides configurations that satisfy all safety and logistics criteria.

### Habitat Configurations

| Parameter | Aluminum | Concrete | Unit |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (from Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Reinforced concrete is a valuable material for lunar habitats. Pareto optimization allows for informed trade-offs between construction effort, technology development, and crew safety. Future work will include higher fidelity radiation codes and non-spherical geometries.