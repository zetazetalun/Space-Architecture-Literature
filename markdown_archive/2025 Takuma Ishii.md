# Distinctive impact responses of extraterrestrial regolith simulants: Insights from crater morphology classification and granular dynamics through machine learning and x-ray computed tomography

**Cite as:** Phys. Fluids 37, 023358 (2025); doi: 10.1063/5.0252502
**Submitted:** 10 December 2024 · **Accepted:** 16 January 2025 · **Published Online:** 12 February 2025

**Authors:** Takuma Ishii, Arata Kioka, Jyh-Jaan Steven Huang, Takeshi Tsuji, Yasuhiro Yamada

## Abstract
Impact responses of granular materials remain poorly understood, posing significant challenges to extraterrestrial exploration activities such as landing, sampling, drilling, and construction. We studied the crater morphology formed in the granular media and their granular behavior on low-velocity impact cratering by integrating three-dimensional surface scanning, machine learning-based classification, and x-ray computed tomography (X-CT) imaging. Our laboratory experiments focused on lunar (LHS-1 and LMS-1) and Martian regolith simulants (MGS-1) and terrestrial fine silica sand (T-8) as studied granular materials. Additionally, our X-CT data emphasized that the high cohesion of LMS-1 significantly enhanced its resistance to impact, resulting in the porosity decline beneath the crater bottom of 0.20 and 0.03 on average in the LHS-1 and LMS-1 media, respectively, when the kinetic energy was 0.3 mJ.

## I. Introduction
The impact behavior of granular materials is crucial for constructing infrastructure on lunar and Martian surfaces. These surfaces are blanketed by regolith, ranging from a few to 10s of meters thick. Understanding the physical and geomechanical properties of regolith is essential for constructing infrastructure and handling materials.

## II. Material and Methodology

### A. Studied granular materials
The study used four granular materials:
- **LHS-1**: Lunar highlands regolith simulant
- **LMS-1**: Lunar mare regolith simulant
- **MGS-1**: Martian global regolith simulant
- **T-8**: Terrestrial silica sand (control)

| Target material | Mean particle density ρg (g/cm³) | Mean particle diameter (μm) | Cohesion (Pa) |
| :--- | :---: | :---: | :---: |
| LHS-1 | 3.23 | 90 | 311 |
| LMS-1 | 3.34 | 91 | 393 |
| MGS-1 | 3.40 | 90 | 307 |
| T-8 | 2.78 | 120 | 0 |

### B. Impact cratering experiments
Spherical alumina projectiles (diameter 8mm and 10mm) were dropped from heights of 10.0 and 15.0 mm. Kinetic energy at contact ranged from 0.1 mJ to 0.3 mJ.

## III. Results and Discussion

### A. Classification with Machine Learning
Logistic regression (LR) models were trained to classify materials based on crater morphology (coefficients from curve fitting, roughness, and curvature). Condition (a)—trained on 10mm drop height craters—showed the best accuracy (0.643).

### B. Slice analysis of CT datasets
- **LHS-1**: Showed a substantial reduction in porosity beneath the crater (approx. 0.20 reduction).
- **LMS-1**: Higher cohesion (393 Pa) led to higher resistance, resulting in smaller craters and a lower porosity decline (0.03 average).
- **T-8**: Showed opposite trends; porosity in the center region actually increased upon impact due to its non-cohesive nature.

## IV. Conclusion
The study bridges the gap between surface crater morphology and subsurface granular behavior. High-fidelity regolith simulants exhibit unique cohesive properties that significantly differ from terrestrial sand, which must be accounted for in extraterrestrial construction and drilling strategies.