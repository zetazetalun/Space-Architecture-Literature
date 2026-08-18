# Distinctive impact responses of extraterrestrial regolith simulants: Insights from crater morphology classification and granular dynamics through machine learning and x-ray computed tomography

**Authors:** Takuma Ishii, Arata Kioka, Jyh-Jaan Steven Huang, Takeshi Tsuji, and Yasuhiro Yamada  
**Publication:** Physics of Fluids 37, 023358 (2025)  
**DOI:** https://doi.org/10.1063/5.0252502

## Abstract
Impact responses of granular materials remain poorly understood, posing significant challenges to extraterrestrial exploration activities such as landing, sampling, drilling, and construction. We studied the crater morphology formed in the granular media and their granular behavior on low-velocity impact cratering by integrating three-dimensional surface scanning, machine learning-based classification, and x-ray computed tomography (X-CT) imaging. Our laboratory experiments focused on lunar (LHS-1 and LMS-1) and Martian regolith simulants (MGS-1) and terrestrial fine silica sand (T-8) as studied granular materials. Profiles were analyzed under kinetic energy at the granular surface contact of 0.1–0.5 mJ. Findings highlight the distinctive granular properties of regolith particles, advancing our understanding of their granular responses to impact.

## I. Introduction
The physical and geomechanical properties of lunar and Martian surfaces remain a fundamental scientific question. The lunar and Martian surfaces are blanketed by a layer of loose granular deposits “regolith,” ranging from a few to 10s meters thick. Constructing infrastructure requires a thorough understanding of the granular properties of regolith. High-fidelity simulants enable controlled laboratory experiments to study various granular properties.

## II. Material and Methodology

### A. Studied granular materials
This paper studied four granular materials with different physical properties (Table I). The simulants include lunar highlands (LHS-1), lunar mare (LMS-1), and Martian global regolith (MGS-1).

**TABLE I. Physical properties of studied granular materials.**

| Target material | Mean particle density ρg (g/cm³) | Mean particle diameter (μm) | Cohesion (Pa) |
| :--- | :--- | :--- | :--- |
| LHS-1 | 3.23 | 90 | 311 |
| LMS-1 | 3.34 | 91 | 393 |
| MGS-1 | 3.40 | 90 | 307 |
| T-8 | 2.78 | 120 | 0 |

### B. Impact cratering experiments
Spherical alumina projectiles (diameter 8 and 10 mm) were dropped from heights of 10.0 and 15.0 mm. Total of 128 impact cratering experiments were conducted.

## III. Results and Discussion

### A. Classification with LR models
The Logistic Regression (LR) model could primarily differentiate studied granular materials based on crater profiles. T-8 was well distinguished from other granular media in all conditions, suggesting significant differences between terrestrial sand and regolith simulants.

**TABLE II. The model performance under conditions (a)–(d).**

| Condition | Training score | Validation score | Logistic regression test accuracy |
| :--- | :--- | :--- | :--- |
| a (10mm drop/15mm test) | 0.841 | 0.836 | 0.643 |
| b (15mm drop/10mm test) | 0.797 | 0.804 | 0.619 |
| c (8mm ball/10mm test) | 0.812 | 0.798 | 0.522 |
| d (10mm ball/8mm test) | 0.782 | 0.789 | 0.292 |

### B. Slice analysis of CT datasets
X-CT imaging analyzed material properties at surface and subsurface levels. The porosity in the “center” region beneath the crater bottom decreased significantly in regolith simulants due to impact, while T-8 showed an increase in porosity in some regions (non-cohesive behavior). High cohesion in LMS-1 (393 Pa) provided greater resistance to impact compared to the nearly noncohesive T-8.

## IV. Conclusion
This study bridges the gap between surface crater morphology and subsurface granular material behavior. High cohesion in regolith simulants significantly influences crater formation and subsurface compaction. These results provide insights for the design of future exploration, drilling, and resource utilization on extraterrestrial terrains.