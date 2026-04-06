# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D.; José Pinto Duarte, Ph.D.
**Publication:** Earth and Space 2024, ASCE
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions to address the challenges of constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) has emerged as a promising technology for building habitats on celestial bodies, such as Mars, due to its adaptability and potential for automated construction. This study aims to lower the printable overhang angle, addressing restrictions posed by a 60-degree limit in horizontal or corbelling slicing techniques. The research explores multi-directional printing with corbelling, radial, and inclined slicing techniques through a sensitivity analysis study on barrel vaults. Results suggest it is possible to maintain the number of printable layers while lowering the overhang angle, constituting a stepstone in the development of a design optimization tool for 3D printed enclosures.

## Introduction
3D printing in space habitat construction is an innovative approach that addresses the challenges of building structures in harsh environments. Teams in NASA's 3D-Printed Habitat Challenge aimed to advance additive construction for sustainable housing on Earth, Moon, Mars, and beyond. Penn State's successful habitat design was contingent on geometry with an overhang angle exceeding 60° due to corbelling limitations. To enable greater design flexibility and lower structures, achieving a lower overhang angle is required. This study explores combining different slicing and multidirectional printing techniques to lower the overhang angle.

## Methodology
The research involves a systematic sensitivity analysis to understand the impact of geometric variables on the buildability of a barrel vault using combined slicing (corbelling and inclined).

### Geometric Variables
- **V1:** Overhang angle of base structure (Constant)
- **V6:** Room width/Span (Constant)
- **V4:** Wall height (H-h) (Independent)
- **V5:** Room length (L) (Independent)
- **V7:** Wall thickness (t) (Independent)
- **V2:** Total height (H) (Dependent)
- **V3:** Pitch height (h) (Dependent)
- **V8:** Number of printable layers (N) (Dependent)

### Slicing Strategies
- **Corbelling:** Horizontal slicing.
- **Inclined Sintering/Slicing:** Slicing at angles (60°, 45°, 30°).
- **Infill Pattern:** Solid concentric infill was used for the analysis.

## Findings
- **Length Impact:** Longer room lengths generally contribute to increased interlayer printing time and a higher potential for printing more layers, up to a certain limit.
- **Trade-offs:** To achieve more printable layers, designers can decrease wall height (H-h) while increasing room length (L), or increase room length while decreasing the printing angle.
- **Thickness:** Greater wall thickness leads to a greater number of printable layers (N).
- **Angle Performance:** Lowering the printing angle allows for a higher percentage of the total structure to be printed before collapse. Specifically, the 30° printing angle configuration yielded the highest level of printability (91%).

## Results
- **Max Printable Layers:** 
  - 60° angle: 134 layers.
  - 45° angle: 132 layers.
  - 30° angle: 132 layers.
- **Printability Percentage:** The 30° printing angle configuration (Type 1d) allowed for 91% of the vault to be printed (132 out of 146 required layers) before predicted collapse.
- **Failure Prediction:** Using a structural behavior simulator, the study identified that shorter wall heights and longer room lengths distinguish the most successful (stable) configurations.

## Conclusion
The sensitivity analysis serves as a tool to perceive patterns leading to structural collapse in 3D printing. The study concludes that multi-directional printing techniques can effectively reduce overhang constraints, which is critical for the design and construction of habitats on Mars and the Moon where formwork is impractical.