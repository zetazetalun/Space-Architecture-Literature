# Concept and preliminary structural analysis of a crater-covering dome for future lunar habitats

**Authors:** Magdalena Mrozek, Dawid Mrozek, Mateusz Smolana, Lorna Anguilano
**Affiliations:** Faculty of Civil Engineering, Silesian University of Technology (Poland); Brunel University London (UK).
**Journal:** Scientific Reports (2025) 15:24744
**DOI:** 10.1038/s41598-025-07901-x

## Abstract
Establishing a habitat on the Moon using In-Situ Resource Utilization (ISRU) is a long-term goal of programs like Artemis. This study analyzes a conceptual lunar habitat created by covering a 17 m diameter crater with a structure made from lunar regolith-based geopolymer. Five shapes were analyzed: two concave domes, a flat circular slab, and two convex domes. Numerical analysis using the Finite Element Method (FEM) revealed that concave-shaped structures are advantageous because internal atmospheric pressure induces compressive stress, which favors the high compressive-to-tensile strength ratio of regolith geopolymer.

## Habitat Categorization
*   **Class I:** Pre-integrated structures manufactured on Earth.
*   **Class II:** Pre-fabricated/deployable/inflatable structures assembled on site.
*   **Class III:** Structures primarily composed of ISRU materials. The authors endorse Class III for its potential for automation and reduced transport costs.

## Materials and Technology
### Lunar Regolith Geopolymer (GP)
*   **Composition:** 10 molar sodium hydroxide (NaOH) solution, sodium silicate water glass (activator), and LHS-1 (highland regolith simulant) as filler.
*   **Curing:** Subjected to a thermal vacuum chamber at 60°C and 50 hPa pressure to simulate lunar conditions.
*   **Mechanical Properties (Tested):**
    *   **Tensile Strength ($f_t$):** 5.5 MPa
    *   **Compressive Strength ($f_c$):** 9.0 MPa
    *   **Young's Modulus ($E$):** 8.13 GPa

### Construction Concepts
*   **Site:** Crater in Mare Tranquillitatis (17 m diameter, 6 m depth).
*   **Geometric Variants (17 m diameter, 0.5 m thick):**
    *   **Case A:** Concave dome (1.0 m rise)
    *   **Case B:** Concave dome (0.5 m rise)
    *   **Case C:** Flat circular slab
    *   **Case D:** Convex dome (0.5 m rise)
    *   **Case E:** Convex dome (1.0 m rise)

## Results of the Structural Analysis

### Vertical Displacement (Central Node)
| Condition [hPa] | Model A (Concave) [cm] | Model C (Flat) [cm] | Model E (Convex) [cm] |
| :--- | :--- | :--- | :--- |
| 0 (Gravity only) | -0.03 | -2.76 | -0.03 |
| 100 | 0.20 | 16.71 | 0.20 |
| 1000 (Earth-like) | 2.25 | 191.98 | 2.25 |

### Maximum Tensile Stress (MPa)
| Condition [hPa] | Model A (Concave) | Model C (Flat) | Model E (Convex) |
| :--- | :--- | :--- | :--- |
| 0 | 0.10 | 1.20 | 0.01 |
| 1000 | 0.62 | 83.10 | 7.03 |
*Note: $f_t$ limit = 5.5 MPa. Model C and E fail at 1000 hPa.*

### Maximum Compressive Stress (MPa)
| Condition [hPa] | Model A (Concave) | Model C (Flat) | Model E (Convex) |
| :--- | :--- | :--- | :--- |
| 0 | 0.00 | 0.00 | -0.07 |
| 1000 | -4.60 | 0.00 | 0.00 |
*Note: $f_c$ limit = -9.0 MPa.*

## Conclusions
*   Concave domes are structurally superior for pressurized lunar habitats as they convert internal pressure into compressive stress.
*   Model A (concave, 1m rise) is the most promising candidate, maintaining stress levels within the material's capacities even at full terrestrial pressure (1000 hPa).
*   Utilizing natural craters reduces material volume and provides passive radiation shielding.