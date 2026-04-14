# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D. and José Pinto Duarte, Ph.D.
**Conference:** Earth and Space 2024
**Publisher:** ASCE
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions for constructing robust, airtight habitats. Additive manufacturing (AM) has emerged as a promising technology for habitats on celestial bodies like Mars. While 3D printing on Earth is effective for walls, challenges persist for roof construction and enclosures. This study explores multi-directional printing using combined horizontal (corbelling) and inclined slicing techniques to lower printable overhang angles (traditionally limited to 60 degrees). A sensitivity analysis using a structural simulator predicts the number of printable layers before collapse. Results suggest it is possible to lower overhang angles while maintaining buildability, providing a step toward design optimization for 3D printed enclosures.

## Introduction
3D printing in space habitat construction addresses challenges in harsh environments, as seen in NASA's 3D-Printed Habitat Challenge. Current 3D Concrete Printing (3DCP) techniques often require a vertical nozzle, limiting overhang angles to approximately 60°. This necessitates pointed arch geometries to avoid formwork. This study explores the hypothesis that combining different slicing techniques can lower these overhang angles, increasing design flexibility for space structures.

## Methodology
The research follows a four-stage workflow:
1.  **Form Generation and Decomposition:** Using shape grammar to break down enclosures into printable patches.
2.  **Sensitivity Analysis:** Using a structural behavior simulator (Duarte et al. 2023) to understand the impact of geometric variables on buildability.
3.  **Transition Strategies:** Determining how to switch between slicing techniques.
4.  **Optimization and Toolpath Generation.**

### Geometric Variables for Sensitivity Analysis
- **V1:** Overhang angle (Constant)
- **V4:** Wall height (Independent)
- **V5:** Room length (Independent)
- **V7:** Wall thickness / Number of filaments (Independent)
- **V8:** Number of printable layers (Dependent)

## Results
Simulation outcomes for vault configurations at 60°, 45°, and 30° printing angles indicate:
-   **30° Angle:** Yielded the highest level of relative printability (91% of the necessary layers for a full vault were successfully simulated).
-   **Room Length:** Longer room lengths generally increase interlayer printing time and potential for more layers, up to a limit (approx. 3m length for 1m wall height).
-   **Wall Thickness:** Increased thickness (more filaments) directly correlates to a higher number of printable layers.
-   **Maximum Layers:** For the tested configurations, the highest number of printable layers achieved were 134 (at 60°), 132 (at 45°), and 132 (at 30°).

## Findings
1. It is feasible to combine corbelling and inclined slicing to achieve overhang angles as low as 45° and 30° without structural collapse during printing.
2. Trade-offs for maximizing printable layers include decreasing wall height while increasing room length, or increasing room length while decreasing the printing angle.
3. Wall thickness is a critical factor in preventing premature structural failure during the additive process.

## Conclusion
This sensitivity analysis demonstrates how geometric variables influence the buildability of 3D printed enclosures. It serves as a foundation for developing design optimization tools to assist in the creation of formwork-free structures for space applications. Future work will involve physical validation through test prints and analysis of collapse modes.