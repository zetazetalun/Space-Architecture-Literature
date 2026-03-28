# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini¹; Sam Wald²; Caitlin Mueller³; Claudio Chesi⁴; and Olivier L. de Weck⁵**

¹Digital Structures Research Group, Dept. of Civil and Environmental Engineering, Massachusetts Institute of Technology
²Dept. of Aeronautics and Astronautics, Massachusetts Institute of Technology
³Digital Structures Research Group, Dept. of Civil and Environmental Engineering, Massachusetts Institute of Technology
⁴Dept. of Architecture, Built Environment and Construction Engineering, Politecnico di Milano
⁵Dept. of Aeronautics and Astronautics, Massachusetts Institute of Technology

## Abstract
Future space habitat structures must protect occupants and provide usable space in extreme, isolated environments. Due to the high cost of transporting resources from Earth, recent efforts focus on Earth-independent designs using local regolith-based materials. This research investigates spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The problem is formulated as a multi-objective optimization to minimize transportation/construction costs and probability of loss due to radiation and micrometeorite events. Pareto optimization identifies efficient design solutions, indicating that ISRU-based reinforced concrete is a valuable investment for lunar and Mars settlements.

## Introduction
Human structures have evolved from using local materials (caves, igloos) to global supply chain structures. Future extraterrestrial shelters require protection from harsh environments. This study investigates reinforced concrete shells across five figures of merit to generalize habitat design space, compared to a baseline aluminum shell.

## Lunar Habitats: Concepts and Materials

### Lunar Concrete for Habitats
Moon colonization requires infrastructure to shelter astronauts. Challenges include temperature cycles, material fatigue, high vacuum effects (out-gassing), and radiation (Solar wind, GCR). Regolith shelters are considered the most meaningful solution for radiation protection.

### Construction Technologies
*   **Foster + Partners/D-Shape:** 3D printing with lunar dust.
*   **Contour Crafting:** Digitally controlled process by Behrokh Khoshnevis using rapid-hardening cement.
*   **Other:** Made In Space, Redworks.

### Structural Concepts
*   **Aluminum Shell:** Baseline system (ISS-like).
*   **Reinforced Concrete Shell:** Spherical dome in regolith. Uses an inner bladder layer in contact with the concrete shell to resist internal pressure. Carbon fiber reinforced polymers (CFRP) provide tensile reinforcement and improved performance against micrometeorite impacts.

## Material Properties

**Table 1. Material properties**

| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## Methodology

### Design Variables
1.  **Interior Radius (X_1):** Overall size (2 to 6 m).
2.  **Tensile Layer Thickness (X_2):** Effective thickness of reinforcement (0.01 to 0.1 m).
3.  **Concrete Layer Thickness (X_3):** Depth of regolith concrete (0 to 0.3 m).

### Evaluation Objectives
1.  **Pressurized Volume:** Maximize habitable space.
2.  **Terrestrial Material Mass:** Minimize mass shipped from Earth.
3.  **Lunar Material Mass:** Minimize mass processed in-situ.
4.  **Impact Protection:** Achieve 0.993 Probability of No Penetration (PMP) over 5 years.
5.  **Radiation Protection:** Minimize Annual Dose Equivalent from GCR.

## Results
Pareto optimal solutions show that reinforced concrete habitats significantly increase protection compared to aluminum. While the minimum dose in aluminum is ~7.5 cSv, the concrete case can reduce this to 5.8 cSv. Concrete's major benefit is its ability to stop meteoroids of masses orders of magnitude greater than aluminum can handle.

**Table 2. Possible habitat configurations with design variables and objectives**

| Variable/Objective | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload | 5435 | 3059 | kg |
| Concrete | 0 | 36283 | kg |
| Meteoroid (max mass) | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## Conclusion
Reinforced concrete is a valuable material for lunar habitats. Pareto optimization allows designers to understand trade-offs between volume, mass, and safety. Future work will refine radiation transport models and explore non-spherical geometries.