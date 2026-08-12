# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D.; and José Pinto Duarte, Ph.D.  
**Publication:** Earth and Space 2024 (ASCE)  
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions for constructing robust, airtight habitats. Additive manufacturing (AM) is a promising technology for habitats on celestial bodies like Mars. This study aims to lower the printable overhang angle (addressing the 60-degree limit of horizontal slicing) by exploring multi-directional printing with corbelling, radial, and inclined slicing techniques. A sensitivity analysis using a structural behavior simulator predicts the number of printable layers until collapse. Results suggest it is possible to maintain printable layers while lowering the overhang angle, providing a step toward design optimization for 3D printed enclosures.

## Introduction
3D printing in space habitat construction addresses the challenges of building in harsh environments. Previous NASA 3D-Printed Habitat Challenges highlighted the need for formwork-free construction. Current 3D Concrete Printing (3DCP) is often limited to vertical walls or pointed arches (overhang > 60°) due to vertical nozzle constraints. This study explores combining different slicing techniques to lower these angles.

## Methodology: Stage 2 Sensitivity Analysis
The research follows a four-stage workflow. This paper focuses on **Stage 2: Sensitivity Analysis**:
1. **Vault Selection**: Barrel vaults for simulation.
2. **Variables**: 
   - *Independent*: Wall height (H-h), room length (L), wall thickness (t/filaments).
   - *Dependent*: Total height (H), number of printable layers (N).
   - *Constant*: Overhang angle (V1), room width (W).
3. **Simulation**: Using an algorithm to predict structural failure modes (plastic collapse, elastic buckling).
4. **Infill**: Solid concentric patterns were analyzed.

## Evaluation of Simulation Outcomes
- **Configuration 1d (Type 1)**: Yielded the highest number of filaments (shorter wall height, longer room length).
- **Printability Percentage**: While the raw number of printable layers was similar across angles, the **30° printing angle** exhibited the highest level of printability, reaching **91%** of the total required layers (132 out of 146 layers).
- **Layer Totals**: The highest number of printable layers for 60°, 45°, and 30° were 134, 132, and 132, respectively.

## Key Findings
- Longer room lengths contribute to increased potential for printing more layers, though this relationship plateaus.
- Trade-offs for printability: Decreasing wall height while increasing room length, or increasing room length while decreasing the printing angle.
- Greater wall thickness (more filaments) directly leads to a higher number of printable layers.
- Lowering the printing angle (e.g., to 30°) allows for a higher percentage of the final structure to be successfully printed.

## Conclusion
This sensitivity analysis provides a tool for perceiving patterns that lead to structural collapse in 3DCP. Future work involves physical validation of these simulations and exploring vaults enclosed by walls on both ends to understand the impact of additional structural elements.