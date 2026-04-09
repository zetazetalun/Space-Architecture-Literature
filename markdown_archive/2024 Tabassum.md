# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D.; and José Pinto Duarte, Ph.D.
**Publication:** Earth and Space 2024, © ASCE
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions for constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) is a promising technology for Mars habitats due to its potential for automated construction. This study aims to lower printable overhang angles (traditionally limited to 60 degrees) by exploring multi-directional printing with corbelling, radial, and inclined slicing techniques. A sensitivity analysis using structural simulations predicts the number of layers until collapse for barrel vaults. Results suggest it is possible to maintain buildability while lowering the overhang angle, providing a stepping stone for design optimization tools.

## Introduction
3D printing addresses challenges of building in harsh environments like Mars. NASA's 3D-Printed Habitat Challenge advanced sustainable housing concepts for the Moon and Mars. Previous successful prints (e.g., Penn State’s second-place design) required overhang angles exceeding 60° due to vertical nozzle limitations. This restriction often limits 3DCP to walls or pointed arches. This study explores combining slicing techniques to achieve lower overhang angles and greater design flexibility.

## Research Workflow
The comprehensive research follows four stages:
1.  **Form Generation and Decomposition:** Using shape grammars to break down enclosures into printable patches.
2.  **Sensitivity Analysis:** Understanding the impact of geometric variables (wall height, room length, wall thickness, printing angle) on buildability.
3.  **Transition Strategies:** Determining toolpath transitions between corbelling and inclined slicing.
4.  **Optimization and Simulation:** Verifying printability through continuous toolpaths.

## Results and Findings
### Simulation Outcomes
*   **Variable Impact:** Shorter wall heights ($H-h = 0.5$ m) and longer room lengths ($L = 4$ m) combined with higher filament counts ($t = 10$) yielded the highest number of printable layers (134 layers).
*   **Printability Percentage:** The 30° printing angle exhibited the highest level of relative printability, with 132 out of 146 required layers (91%) being printable before structural failure.
*   **Thickness Correlation:** Increased wall thickness (number of filaments) directly correlates to a higher number of printable layers ($N$).

### Key Findings
*   Longer room lengths increase interlayer printing time, which can improve the potential for printing more layers up to a certain limit.
*   Lowering the printing angle allows for a greater number of printable layers.
*   Trade-offs for increased buildability include decreasing wall height while increasing room length, or increasing room length while decreasing the printing angle.

## Conclusion
This sensitivity analysis provides a nuanced understanding of how geometric variables influence the buildability of 3D-printed enclosures. The next steps involve physical validation through test prints and investigating collapse modes to refine the simulation tool for complex vault designs.