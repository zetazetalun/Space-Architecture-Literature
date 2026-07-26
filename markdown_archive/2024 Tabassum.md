# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D.; José Pinto Duarte, Ph.D.  
**Publication:** Earth and Space 2024 (ASCE)  
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions to address the challenges of constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) has emerged as a promising technology for building habitats on celestial bodies, such as Mars, due to its adaptability and potential for automated construction. While 3D printing techniques on Earth have proven effective for building components, challenges persist in printing enclosures and the utilization of various mixed fabrication methods for roof construction. The study aims to lower the printable overhang angle, addressing restrictions posed by a 60-degree limit in horizontal or corbelling slicing techniques. Inspired by historical bricklaying, the research explores multi-directional printing with corbelling, radial, and inclined slicing techniques. The paper focuses on a sensitivity analysis study aimed at understanding the impact of geometric variables on the printability of barrel vaults using combined horizontal and inclined slicing techniques. Results suggest that it is possible to maintain the number of printable layers while lowering the overhang angle.

## Introduction
3D printing in space habitat construction is an innovative approach that addresses the challenges of building structures in harsh environments. Teams in NASA's 3D-Printed Habitat Challenge aimed to advance additive construction for sustainable housing on Earth, Moon, and Mars. Penn State secured second place with an enclosed habitat design that was successfully 3D printed without formwork, though this was contingent on geometry having an overhang angle exceeding 60°. To enable greater design flexibility, achieving a lower overhang angle is required. This study explores the hypothesis that combining different slicing and multidirectional printing techniques (corbelling and inclined slicing) makes it possible to lower the overhang angle.

## Methodology
The research utilizes a simulation-based sensitivity analysis (Stage 2 of a broader workflow) to understand the impact of geometric variables on buildability. 

### Geometric Variables:
- **Independent Variables:** Wall height ($H-h$), Room length ($L$), Wall thickness ($t$).
- **Dependent Variables:** Total height ($H$), Pitch height ($h$), Number of printable layers ($N$).
- **Constant Variables:** Overhang angle of base structure ($\alpha^o$), Room width/Span ($W$).

### Simulation Protocol:
- Wall height: 0.5 m and 1 m
- Room length: 1, 2, 3, 4 m
- Wall thickness (filaments): 2, 4, 6, 8, 10 filaments
- Printing angles: 60°, 45°, and 30°

## Results & Findings

### Key Findings:
1. **Infill & Thickness:** A greater wall thickness (number of filaments) leads to a higher number of printable layers ($N$).
2. **Geometric Tradeoffs:** To achieve more printable layers, designers can decrease the vertical wall height while increasing room length, or increase room length while decreasing the printing angle.
3. **Angle Efficiency:** The 30° printing angle exhibited the highest level of relative printability; it allowed for printing 132 layers, representing 91% of the total vault height required.
4. **Length Limits:** While longer room lengths generally allow for more layers due to increased interlayer printing time (allowing material to gain strength), this relationship plateaus when room dimensions exceed specific ratios (e.g., wall height 1m/room length 3m).

### Data Points (Best Outcomes):
- **60° Printing Angle:** 134 printable layers (59% of fabrication).
- **45° Printing Angle:** 132 printable layers (71% of fabrication).
- **30° Printing Angle:** 132 printable layers (91% of fabrication).

## Conclusion
Sensitivity analysis serves as a valuable tool for perceiving patterns leading to structural collapse in 3DCP. This study demonstrates that combining corbelling and inclined slicing can effectively reduce the overhang angle needed for roof construction without formwork, a critical requirement for autonomous extraterrestrial construction.