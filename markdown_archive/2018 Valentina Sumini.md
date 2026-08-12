# Multiobjective Optimization for Structural Design of Lunar Habitats

**Authors:** Valentina Sumini, Sam Wald, Caitlin Mueller, Claudio Chesi, and Olivier L. de Weck
**Affiliations:** MIT (Digital Structures Research Group, Dept. of Aeronautics and Astronautics), Politecnico di Milano
**Source:** Earth and Space 2018, ASCE

### Abstract
Future space habitat requirements include protecting occupants and providing usable space in extreme environments. This research investigates Earth-independent structural designs using local regolith-based materials. It focuses on spherical regolith-based concrete shells reinforced with carbon fiber polymer. A multi-objective optimization approach is used to minimize transportation/construction costs and probability of loss due to radiation and micrometeorites. Pareto optimization identifies design elements that offer the greatest efficiency, suggesting ISRU-based reinforced concrete is a valuable future investment for Lunar and Mars settlements.

### Introduction and Prior Studies
The paper references various habitat concepts, including inflatable structures protected by catenary regolith shells and 3D-printed habitats using technologies like D-Shape and Contour Crafting. The goal is to move from Class I (pre-fabricated) and Class II (deployable) habitats toward Class III (ISRU-based) structures to reduce the prohibitively high cost of shipping materials from Earth.

### Methodology
The study evaluates spherical geometries defined by interior radius, tensile layer thickness (CFRP), and concrete layer thickness. Five primary objectives are assessed:
1. **Pressurized Volume:** Maximizing habitable space.
2. **Terrestrial Material Mass:** Minimizing mass launched from Earth.
3. **Lunar Material Mass:** Minimizing the complexity and cost of ISRU processing.
4. **Impact Protection:** Ensuring a 0.993 Probability of No Penetration (PMP) over 5 years.
5. **Radiation Protection:** Minimizing the Radiation Dose Equivalent from Galactic Cosmic Rays (GCR).

### Material Properties
| Property | Units | Value |
| :--- | :--- | :--- |
| Concrete density | Kg/m³ | 2200 |
| Concrete allowable stress | Pa | 33.8*10⁶ |
| Aluminum density | Kg/m³ | 2700 |
| Aluminum tensile allowable stress | Pa | 280*10⁶ |

### Results
The analysis compared a baseline aluminum shell with a reinforced concrete shell. Results indicate that while aluminum shells are limited by tensile thickness constraints, concrete shells can significantly reduce radiation doses. For a 180-day mission, the concrete case reduced GCR exposure from ~7.5 cSv to 5.8 cSv at maximum thickness and provided vastly superior protection against high-mass micrometeoroids.

### Possible Habitat Configurations (Table 2)
| Parameter | Aluminum | Concrete | Units |
| :--- | :--- | :--- | :--- |
| Radius | 4.22 | 4.67 | m |
| Tensile Thickness | 0.009 | 0.012 | m |
| Regolith Thickness | 0 | 0.059 | m |
| Volume | 316 | 426 | m³ |
| Payload (from Earth) | 5435 | 3059 | kg |
| Concrete (Lunar) | 0 | 36283 | kg |
| Meteoroid (Mass limit) | 2.94e-6 | 1.04e-5 | kg |
| Dose | 15.3 | 9.7 | cSv |

### Conclusion
ISRU-based reinforced concrete offers a viable path for sustainable habitat construction. Pareto optimization allows designers to navigate trade-offs between safety (radiation/impact) and cost (launch mass). In the examined scenarios, the aluminum baseline could not satisfy all performance goals simultaneously, whereas the concrete typology provided several valid solutions.