# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Conference Paper** · October 2024  
**DOI:** 10.1061/9780784485736.073  

**Authors:**
- Nusrat Tabassum, Ph.D. (Pennsylvania State University)
- José Pinto Duarte, Ph.D. (Pennsylvania State University)

## ABSTRACT
Architecture in space demands innovative solutions to address the challenges of constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) has emerged as a promising technology for building habitats on celestial bodies, such as Mars, due to its adaptability and potential for automated construction. While 3D printing techniques on Earth have proven effective for building components, challenges persist in printing enclosures and the utilization of various mixed fabrication methods for roof construction. The study aims to lower the printable overhang angle, addressing restrictions posed by a 60-degree limit in horizontal or corbelling slicing techniques. Inspired by historical bricklaying, the research explores multi-directional printing with corbelling, radial, and inclined slicing techniques. The paper focuses on a sensitivity analysis study aimed at understanding the impact of geometric variables on the printability of barrel vaults using combined horizontal and inclined slicing techniques. A simulator of structural behavior during printing developed previously is used to predict the number of printed layers until collapse. Results suggest that it is possible to maintain the number of printable layers while lowering the overhang angle. While these results still need to be validated through printing experiments, they constitute a stepstone in the development of a design optimization tool to assist in the design of 3D printed enclosures.

## INTRODUCTION
3D printing in space habitat construction is an innovative approach that addresses the challenges of building structures in harsh environments. The teams who participated in NASA's competition to design a 3D-printed habitat for Mars aimed to advance additive construction for sustainable housing on Earth, Moon, Mars, and beyond. Penn State secured second place with an enclosed habitat design. However, successful printing without formwork was contingent on geometry having an overhang angle exceeding 60° due to corbelling limitations. To enable greater design flexibility and lower structures, achieving a lower overhang angle is required.

## OVERVIEW OF THE COMPREHENSIVE RESEARCH
The primary research aim is to decrease the current overhang angle constraints in 3D concrete printing (3DCP) to facilitate the printing of enclosures without formwork using multi-directional printing. 

### Sensitivity Analysis Workflow
1. Select the vault type for simulation.
2. Determine variables to manipulate (Wall height, room length, wall thickness).
3. Conduct simulations to determine the maximum number of printable layers.
4. Analyze collapse modes.
5. Select optimal printing options.

### Geometric Variables
- **V1:** Overhang angle of base structure (α°)
- **V4:** Wall height (H-h)
- **V5:** Room length (L)
- **V7:** Wall thickness (t) / Number of filaments (Nf)
- **V8:** Number of printable layers (N)

## FINDINGS
- **Room Length Impact:** Longer room lengths generally contribute to increased interlayer printing time and a higher potential for printing more layers, though this relationship has a limit.
- **Trade-offs for Printability:** To achieve more printable layers, designers can decrease wall height (H-h) while increasing room length (L), or increase room length (L) while decreasing the printing angle.
- **Thickness:** A greater wall thickness leads to a greater number of printable layers.
- **Lower Angles:** A greater number of printable layers is possible by lowering the printing angle (e.g., to 30°).

## CONCLUSION
This sensitivity analysis represents an intermediate stage in comprehending the intricacies of the 3D printing process. It serves as a tool to perceive patterns leading to structural collapse. Future work involves validating these simulation outcomes through physical test prints and analyzing collapse modes to refine the simulation tool.