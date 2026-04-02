# Determining the yield stress of a Biopolymer-bound Soil Composite for extrusion-based 3D printing applications

**Authors:** Adrian Biggerstaff, Gerald Fuller, Michael Lepech, David Loftus  
**Journal:** Construction and Building Materials 305 (2021) 124730  
**Published:** 8 September 2021

## Abstract
Biopolymer-bound Soil Composite (BSC) is a novel class of construction materials with potential use in extraterrestrial infrastructure development and more sustainable construction on Earth. Little is known about the rheological properties of this new material and its suitability for extrusion-based 3D printing (E3DP). This paper presents methods for testing BSC yield stress and proposes hydrodynamic and frictional yield stress models for predicting the static and dynamic yield stress of BSC mixtures. Using experimental results, a soil volume fraction range for BSC is identified that may be suitable for E3DP based on extrudability and shape stability requirements.

## 1. Introduction
Extrusion-based 3D printing (E3DP) has emerged as a viable alternative to form-based construction methods. Materials for E3DP must balance low yield stress/viscosity (for pumpability) with sufficiently high yield stress (for shape stability post-extrusion). 

BSC mixtures are being explored as sustainable alternatives to cement. Specifically, BSC has potential for extraterrestrial construction on the Moon and Mars using In Situ Resource Utilization (ISRU). The study explores BSC consisting of lunar regolith simulant (JSC-1A), bovine blood proteins (binder), and deionized water.

## 3. Materials and Methods
Seven BSC mixtures were evaluated using JSC-1A lunar regolith simulant and bovine blood proteins (AP920).

### Table 1: Biopolymer-Bound Soil Composite (BSC) Mixtures
| Mix Name | Biopolymer Sol. Conc. (% w/w) | Biopolymer-Soil Ratio (% w/w) | Density (kg/m³) | Soil Vol Fraction (φBSC) | Avg. Slump (mm) | φBSC/φmp |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| 35–20 | 35.2% | 19.9% | 1454 | 0.321 | 39.5 | 46.6% |
| 35–15 | 35.0% | 14.9% | 1654 | 0.402 | 31.5 | 58.3% |
| 35–12.5 | 35.0% | 12.4% | 1793 | 0.459 | 26.9 | 66.6% |
| 35–11 | 34.5% | 11.0% | 1868 | 0.494 | 14.4 | 71.7% |
| 35–10 | 35.4% | 10.0% | 1920 | 0.519 | 8.7 | 75.3% |
| 36–10 | 36.1% | 10.0% | 1920 | 0.522 | 7.4 | 75.8% |
| 38–10 | 37.9% | 10.0% | 1988 | 0.548 | 5.1 | 79.5% |

## 5. Yield Stress Modeling
- **Hydrodynamic Regime:** Modeled using the Chateau-Ovarlez-Trung (COT) model for dynamic yield stress (τdys).
- **Frictional Regime:** Modeled using De Larrard’s (DL) model for static yield stress (τsys).

### Yield Stress Equations
Static Yield Stress:  
$$τ_{sys} = (1Pa)e^{\left(\frac{3.21+0.85 \phi_{BSC}/0.643}{1- \phi_{BSC}/0.643}\right)}$$  

Dynamic Yield Stress (up to φ = 0.52):  
$$τ_{dys} = 1.26Pa \sqrt{(1 - \phi)(1 - \phi_{BSC}/0.560)^{-9.42(0.560)}}$$

## 7. Conclusion
BSC using low-cohesion soil (lunar simulant) is suitable for E3DP within a soil volume fraction range of 0.435 ≤ φBSC ≤ 0.548. The lower bound ensures shape stability (min 5mm height), while the upper bound (80% of maximum packing fraction) ensures extrudability through standard nozzles.