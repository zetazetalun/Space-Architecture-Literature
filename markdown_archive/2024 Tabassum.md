# Exploring Multi-Directional 3D Printing for Enclosures on Earth and Beyond: Sensitivity Analysis of Buildability

**Nusrat Tabassum, Ph.D.** and **José Pinto Duarte, Ph.D.**  
Dept. of Architecture, College of Arts and Architecture, Pennsylvania State Univ.

## Abstract
Architecture in space demands innovative solutions to address the challenges of constructing robust, airtight habitats on extraterrestrial surfaces. Additive manufacturing (AM) has emerged as a promising technology for building habitats on celestial bodies, such as Mars, due to its adaptability and potential for automated construction. This study aims to lower the printable overhang angle, addressing restrictions posed by a 60-degree limit in horizontal or corbelling slicing techniques. Inspired by historical bricklaying, the research explores multi-directional printing with corbelling, radial, and inclined slicing techniques. A sensitivity analysis study focuses on understanding the impact of geometric variables on the printability of barrel vaults. Results suggest that it is possible to maintain the number of printable layers while lowering the overhang angle.

## Introduction
3D printing in space habitat construction addresses challenges in harsh environments. NASA's competition for a Mars habitat advanced additive construction for the Moon, Mars, and beyond. Penn State secured second place with a design that was 3D printed without formwork, but limited by a 60° overhang angle restriction using vertical nozzles. This study explores the hypothesis that combining different slicing and multidirectional printing techniques can lower the overhang angle, increasing design flexibility.

## Methodology: Overview of Research
The primary aim is to decrease overhang constraints (below 60°) to facilitate enclosures without formwork. The research involves:
1.  Selecting vault types.
2.  Decomposing geometry into printable patches.
3.  Slicing patches (corbelling vs. inclined).
4.  Systematic sensitivity analysis.
5.  Determining transition strategies.
6.  Defining thickness and infill (solid concentric).
7.  Generating toolpaths.
8.  Optimizing and simulating structural behavior during printing.

### Stage 1: Form Generation and Decomposition
A shape grammar was developed to parametrically encode vault forms and decompose them into patches. Validation included a 3D-printed barrel vault section with a 45° overhang angle.

### Stage 2: Sensitivity Analysis
Simulations used an algorithm to predict structural failure (plastic collapse, buckling). Variables included:
- **Independent:** Wall height (H-h), Room length (L), Wall thickness (t).
- **Dependent:** Total height (H), Pitch height, Number of printable layers (N).
- **Angles:** 60°, 45°, and 30° inclined slicing.

## Results and Evaluation
Analysis of simulation outcomes for vault configurations:
- **Configuration 1d (Type 1):** Yielded the highest number of filaments (shorter wall height, longer room length).
- **Printability Percentage:** While the absolute number of layers was similar across angles, the 30° printing angle exhibited the highest level of relative printability (91% of the total vault could be printed).
- **Layer Counts:** The highest number of printable layers for 60°, 45°, and 30° were 134, 132, and 132, respectively.
- **Thickness Impact:** Greater wall thickness (t) leads to a greater number of printable layers (N).

## Findings
1. Longer room lengths contribute to increased interlayer printing time and higher potential for more layers, up to a certain limit.
2. Trade-offs for more printable layers include decreasing wall height while increasing room length, or increasing room length while decreasing the printing angle.
3. Lowering the printing angle allows for a greater number of printable layers relative to the total design height.

## Conclusion
This sensitivity analysis serves as an intermediate tool to perceive patterns leading to structural collapse. Future work involves physical validation through test prints and simulating vaults enclosed by walls on both ends to assist in the design of space enclosures.