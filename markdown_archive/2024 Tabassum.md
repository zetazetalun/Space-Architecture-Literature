# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Authors:** Nusrat Tabassum, Ph.D.; José Pinto Duarte, Ph.D.
**Publication:** Earth and Space 2024, ASCE
**DOI:** 10.1061/9780784485736.073

## Abstract
Architecture in space demands innovative solutions to address the challenges of constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) has emerged as a promising technology for building habitats on celestial bodies, such as Mars, due to its adaptability and potential for automated construction. This study aims to lower the printable overhang angle, addressing restrictions posed by a 60-degree limit in horizontal or corbelling slicing techniques. Inspired by historical bricklaying, the research explores multi-directional printing with corbelling, radial, and inclined slicing techniques. The paper focuses on a sensitivity analysis study aimed at understanding the impact of geometric variables on the printability of barrel vaults using combined horizontal and inclined slicing techniques.

## Introduction
3D printing in space habitat construction addresses challenges in harsh environments. Teams in NASA's 3D-printed habitat challenge aimed to advance additive construction for sustainable housing on Earth, Moon, and Mars. Penn State secured second place with a design that was printed without formwork, though limited to geometries with overhang angles exceeding 60°. This study explores the hypothesis that combining different slicing and multidirectional printing techniques can lower the required overhang angle.

## Overview of the Comprehensive Research
The primary research aim is to decrease current overhang angle constraints to facilitate the printing of enclosures without formwork. The methodology includes:
1. Select vault type.
2. Decompose geometry into printable patches.
3. Slice patches into layers.
4. Run systematic sensitivity analysis.
5. Determine transition strategies between corbelling and inclined slicing.
6. Define structure thickness, filament count, and infill pattern.
7. Generate continuous toolpath.
8. Optimize and simulate.
9. Verify printability.

## Stage 2: Sensitivity Analysis
An experimental program was devised to understand the impact of geometric variables on the buildability and printability of the vault. 

### Geometric Variables:
- **Constants:** Overhang angle of base structure (V1), Room width/Span (V6).
- **Independent Variables:** Wall height (V4), Room length (V5), Wall thickness (V7).
- **Dependent Variables:** Total height (V2), Pitch height (V3), Number of printable layers (V8).

### Simulation Results Summary
- **60° Printing Angle:** Max printable layers reached 134 (shorter wall height, longer room length).
- **45° Printing Angle:** Max printable layers reached 132.
- **30° Printing Angle:** Max printable layers reached 132.
- **Printability Percentage:** The 30° printing angle exhibited the highest level of printability (91% of total required layers), meaning it could print almost the entire vault before collapse.

## Findings
- Longer room lengths contribute to increased interlayer printing time and a higher potential for printing more layers, up to a certain limit.
- To achieve more printable layers, trade-offs involve decreasing wall height while increasing room length, or increasing room length while decreasing the printing angle.
- Greater wall thickness (increased filament count) leads to a greater number of printable layers.
- Lowering the printing angle (e.g., to 30°) increases the total percentage of the structure that can be successfully printed.

## Conclusion
Sensitivity analysis serves as a tool to perceive patterns leading to structural collapse in 3DCP. Future work involves validating simulation outcomes through physical test prints and simulating vaults enclosed by walls on both ends to understand the impact of additional structural elements.