# Multiscale Modeling and Testing of Protein-Bound Regolith and Soils

**I. Rosa**; **M. D. Lepech**; and **D. J. Loftus**

## ABSTRACT
Extraterrestrial construction presents many interesting and new challenges. Unlike Earth, there are very limited naturally occurring resources readily available in extraterrestrial environments, such as the Moon or Mars. Transporting large amounts of materials from Earth is cost prohibitive. Thus, this work focuses on a novel class of composites for use in limited resource environments: protein-bound soils. The composite is produced by mixing soil, water, and a biopolymer binder (protein or other biopolymer) to create a versatile composite with compressive strength comparable to that of ordinary Portland cement concrete. This paper proposes a multi-scale framework to model the composite’s fracture properties in order to design a durable material that can resist extreme environments.

## INTRODUCTION
One of the most challenging aspects of space surface operations is providing protection to both equipment and personnel. NASA's *Journey to Mars Roadmap* (2015) identifies *in situ resource utilization* (ISRU) as key to reducing exploration costs. Regolith has the potential to provide raw materials for radiation shielding. Protein-bound regolith offers a low-energy, in situ construction material for structures, roads, and landing pads.

### Material Composition and Microstructure
- **Binder:** Desiccated proteins (e.g., bovine serum albumin) at 5-15% by weight.
- **Matrix:** Lunar or Martian regolith simulant.
- **Porosity:** 20-40% (compared to 7-20% for Portland cement).
- **Mechanism:** Protein coats soil particles and forms film bridges connecting adjacent particles.

## DEVELOPMENT OF A MULTISCALE FRAMEWORK
The framework integrates four scales:
1. **Nanoscale:** Nanoindentation to find the linear elastic properties of dried protein.
2. **Microscale:** Statistically Equivalent Periodic Unit Cells (SEPUC) based on MicroCT scans to capture soil-protein-void interactions.
3. **Mesoscale:** Rigid Body Spring Model (RBSM) to simulate crack propagation and fracture in homogenized material.
4. **Macroscale:** Uniaxial and triaxial testing (aided by Digital Image Correlation) to validate models and understand failure yield surfaces.

## RESULTS AND COMPARISON
| Property | Portland Cement Mortar | Protein-Bound Regolith |
| :--- | :--- | :--- |
| Compressive Strength | ~35 MPa | ~12 MPa |
| Stiffness (Young's Modulus) | ~22 GPa | ~1.2 GPa |
| Porosity | 7 - 20% | 20 - 40% |
| Binder Young's Modulus | 10 - 25 GPa | ~4 MPa (Estimated) |

## CONCLUSIONS & FUTURE WORK
The multiscale framework allows for the prediction of mechanical properties based on mix design. Future work will include optimizing mix designs for specific environments and extending the model to the system scale for full-scale extraterrestrial structures.