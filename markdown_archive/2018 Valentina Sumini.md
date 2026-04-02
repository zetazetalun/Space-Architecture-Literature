# Multiobjective Optimization for Structural Design of Lunar Habitats

**Valentina Sumini¹; Sam Wald²; Caitlin Mueller³; Claudio Chesi⁴; and Olivier L. de Weck⁵**

¹Digital Structures Research Group, Dept. of Civil and Environmental Engineering, MIT
²Dept. of Aeronautics and Astronautics, MIT
³Digital Structures Research Group, Dept. of Civil and Environmental Engineering, MIT
⁴Dept. of Architecture, Built Environment and Construction Engineering, Politecnico di Milano
⁵Dept. of Aeronautics and Astronautics, MIT

## ABSTRACT

Much like their Earth-based counterparts, the requirements of future space habitat structures can be defined by their ability to protect their occupants and provide usable space to live and work in an extreme, isolated environment. Due to the high cost of transporting resources off of Earth’s surface, recent efforts focus on developing increasingly Earth-independent structural designs. These new designs use local regolith-based materials as a possible solution for long-term extraterrestrial sustainability. With a focus on an Earth-independent habitat, this research looks at architectures that use spherical regolith-based concrete shells with carbon fiber polymer reinforcement. The research approach is to formulate the structural design problem as a multi-objective optimization of the habitat shell. The objectives include the minimization of transportation and construction costs, and the minimization of the probability of loss due to radiation and micrometeorite events. Direct trade-offs arise. The authors examine candidate design solutions based on priorities and performance thresholds which indicate that ISRU-based reinforced concrete may be a valuable future investment. While the cases presented here are limited to lunar surface systems, both the general architectures and the methodology for analysis and design are applicable to future Mars settlements.

## INTRODUCTION

Humans have relied on structures for protection for thousands of years, using local materials (e.g., caves, igloos) or mobile systems (yurts). In the potential futures of the human species, it may prove necessary to move beyond Earth. However, protection from harsh environments is required. Recent efforts have focused on developing Earth-independent structural designs that use local regolith-based materials for long-term sustainability. We investigated the impact of material geometrical variables on reinforced concrete shells in five figures of merit compared to a baseline aluminum shell case.

## PRIOR STUDIES ON LUNAR HABITAT STRUCTURAL OPTIMIZATION

Previous studies investigated pressurized aluminum dome habitats (Ruess 2006), inflatables inside protective catenary shells (Benvenuti 2013), and optimal radiation shielding (Tripathi 2001). Bodiford (2006) performed a multi-objective trade study of ten construction approaches. San Soucie (2007) used genetic algorithms for dome-type shells. This research builds on these by applying multi-objective evaluation to pressurized domed habitats constructed from regolith-based concrete reinforced with Earth-sourced materials.

## LUNAR HABITATS: CONCEPTS AND MATERIALS

### Lunar Concrete for Habitats
Establishing a manned colony on the Moon or Mars requires infrastructure to shelter astronauts. Designing for the lunar surface involves addressing temperature cycles, material fatigue, high vacuum effects (out-gassing), and new failure modes like micrometeorite impacts. Due to the absence of a magnetic field and atmosphere, regolith shelters are considered the most meaningful solution for radiation protection.

Literature mentions Foster + Partners' design using D-Shape 3D printing technology and Neil Leach/Behrokh Khoshnevis' Contour Crafting for robotic fabrication. Using local materials is critical due to transportation costs (estimated at US$ 2 million per brick).

*   **Aluminum Shell:** Represents typical systems used in the ISS.
*   **Reinforced Concrete Shell:** Considers a spherical dome in regolith with an inner bladder layer in contact with the concrete shell. Carbon fiber reinforced polymers (CFRP) are used to resist tension stresses and enhance micrometeorite performance.

### Material Properties

Expected material strength for regolith is assumed between 10 and 100 MPa with a density between 1000 to 3000 kg/m³.

**Table 1. Material properties**

| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

## METHODOLOGY

### Primary Structure Generation and Evaluation Process
Geometries are defined by three variables: interior radius ($X_1$), thickness of shell tensile layer ($X_2$), and thickness of concrete layer ($X_3$). Feasible geometries are evaluated on five objectives:
1.  Internal pressurized volume (maximize)
2.  Material mass from Earth (minimize)
3.  Material mass from Moon (minimize)
4.  Radiation protection (maximize/minimize dose)
5.  Meteoroid protection (maximize mass resisted)

## RESULTS

Variable ranges were restricted to: $X_1 = [2, 6]m$, $X_2 = [0.01, 0.1]m$, $X_3 = [0, 0.3]m$. Results show that maximum payload from Earth is reduced for CFRP-reinforced systems due to high strength/low density compared to aluminum. Reinforced concrete habitats significantly increase protection against meteoroids and radiation.

## DISCUSSION

Performance goals include a recommended volume of 226 m³ for 4 crew over 180 days. A reference mass of 55,000 kg of concrete is assumed to be produceable in-situ based on one lander's capacity.

**Table 2. Possible habitat configurations with design variables and objectives for aluminum and concrete typologies.**

| | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload | 5435 | 3059 | kg |
| Concrete | 0 | 36283 | kg |
| Meteoroid | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

## CONCLUSION

Pareto optimization allows decision-makers to understand trade-offs without pre-weighting priorities. Reinforced concrete is a valuable material for further investigation in lunar habitat structures to balance cost and safety.