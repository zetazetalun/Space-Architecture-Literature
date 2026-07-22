# Multi-scale modeling of hydrogel-based concrete formed under the ambient environment and the extremely harsh environment of Mars

**Journal:** Journal of the Mechanics and Physics of Solids, 196 (2025) 105969  
**Authors:** Ning Liu, Tianju Xue, Jishen Qiu  
**Affiliation:** Hong Kong University of Science and Technology  
**DOI:** https://doi.org/10.1016/j.jmps.2024.105969

## Abstract
Hydrogel-based concretes (HBCs) are load-bearing composites consisting of inert particles joined by micro-hydrogel joints. They harden via sol-gel processes and H2O phase changes under freezing temperatures and vacuum, making them suitable for extraterrestrial construction. This study presents a multi-scale model predicting mechanical properties under Martian conditions. On the micro-scale, four joint microstructures (tubular, foamy, honeycomb, tube-cased-foam) are analyzed. On the macro-scale, a Discrete Element Method (DEM)-based model is employed to quantify interparticle relationships using a linear parallel bond model (LPM) and Weibull distribution for joint strength variation. Results accurately predict the influence of mix design and curing conditions on mechanical properties.

## Nomenclature
- **Aj, Ap:** Area of cross section of joints, peeled skin
- **D0:** Diameter of particles
- **d0:** Diameter of fresh hydrogel
- **dmax, dmin, h, t, t':** Geometric dimensions of post-curing joints
- **Es, Gs:** Elastic and shear modulus of gel material
- **Fn, Fs:** Applied normal and shear force
- **Kn, Ks:** Normal and shear stiffness
- **s/a:** Hydrosol-to-aggregate weight ratio
- **σf, τf:** Failure strength of gel

## 1. Introduction
HBC is potential for resource-starved and extremely harsh environments like the Moon or Mars. Production requires minimal non-local material (20 kg/m3 polymer) and energy compared to laser/microwave sintering of regolith. Hardening occurs at sub-zero temperatures (-55 °C) and reduced pressure (0.01% atm) through water freezing and sublimation (freeze-drying).

## 2. Methodology
### 2.1 Micro-scale
- **Specimens:** Two spherical glass beads (20 mm) joined by gelatin-based hydrosol.
- **Curing regimes:** Air-drying (AD: 23 °C, 1 atm) and Freeze-drying (FD: -18 °C then -55 °C, 10 Pa).
- **Joint Types:** Tubular (AD, low s/a), Honeycomb (AD, high s/a), Tube-cased foam (FD, low s/a), Foamy (FD, high s/a).

### 2.2 Macro-scale (DEM Model)
- **Geometry:** 40 mm HBC cube, ~7963 particles (1.0-1.3 mm), ~31,853 joints.
- **Bonding:** Linear Parallel Bond Model (LPM).
- **Variability:** Weibull probability distribution applied to joint strengths (homogeneity index m=6).

## 3. Key Findings & Results
### 3.1 Joint Behavior
- **Tubular joints:** Exhibit two-stage failure (elastic elongation followed by skin-peeling/debonding).
- **Foamy joints:** Linear elastic ramp followed by multiple drops due to internal cellular failure.

### 3.2 HBC Compressive Performance
- **Mix Design Effect:** Increasing s/a ratio consistently increases compressive strength. Elastic modulus increases then decreases as s/a exceeds a threshold.
- **Curing Effect:** Air-dried (AD) HBC exhibits significantly higher elastic modulus and compressive strength compared to freeze-dried (FD) counterparts due to thicker micro-tube walls vs. thin foamy structures.
- **Failure Modes:** Low s/a samples show brittle diagonal cracking; high s/a (0.2) freeze-dried samples show multiple cracks and enhanced ductility.

### 3.3 Modeling Accuracy
- The DEM model accurately captures stress-strain curves up to large strains when Weibull distributions are used to account for joint heterogeneity.

| Curing | s/a | Type | Tension Kneq (N/mm) | Tension Failure Force (N) | Shear Kseq (N/mm) | Shear Failure Force (N) |
|---|---|---|---|---|---|---|
| AD | 0.05 | Tubular | 8.72 | 0.83 | 5.45 | 0.42 |
| AD | 0.1 | Tubular | 10.71 | 1.69 | 6.68 | 1.35 |
| AD | 0.2 | Honeycomb | 10.18 | 3.05 | 6.43 | 2.38 |
| FD | 0.05 | Tube-Foam | 6.71 | 0.51 | 2.21 | 0.42 |
| FD | 0.2 | Foam | 6.99 | 0.78 | 1.28 | 0.61 |