# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024) 19:1379–1396  
**DOI:** https://doi.org/10.1007/s11440-023-02119-5  

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. Seeking an optimal lunar drill design with effective and efficient controlling strategies has become a matter of urgency. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill design into the lunar regolith using the discrete element method (DEM). The framework optimizes geometry (anchor height, shape, and cone apex angle) and controlling strategies (downward velocity, rotation velocity, expansion velocity, and anchor-cone distance) to minimize construction cost and power consumption while maximizing drilling effectiveness and efficiency.

## 1 Introduction
Artemis missions highlight the necessity for unitizing in situ resources on the Moon for long-term exploration. Geotechnical characterization via drilling is a prerequisite for construction. Challenges include significantly different regolith properties, lack of human operators, and high transportation costs for heavy equipment. Bio-inspired strategies, such as clam-inspired drilling, offer low-cost and sustainable solutions for subsurface exploration.

## 2 Methodology
### 2.1 Numerical Modeling
- **Software:** PFC3D (Particle Flow Code) version 7.0.
- **Simulant:** Lunar highlands simulant (LHS-1).
- **Drilling Phases:** 
  1. Phase I: Cone penetration.
  2. Phase II: Anchor expansion.
  3. Phase III: Self-penetration.
- **Gravity:** 1.625 m/s².

### 2.2 Optimization Framework
- **Stage 1:** Geometry Optimization (Objective: Minimize Cost and Power Consumption).
- **Stage 2:** Strategy Optimization (Objective: Maximize Effectiveness and Efficiency).

## 3 Results
### 3.1 Drill Geometry
- **Anchor Height (H):** Shorter anchor heights are advantageous to reduce cone tip resistance ($Q_c$) due to localized stress relaxation.
- **Anchor Shape (b):** Cylinder-shaped anchors ($b = \infty$) are more effective at penetration reduction than arc-shaped anchors, but surface area tradeoffs favor specific curvatures.
- **Cone Apex Angle (α):** Blunter tips (larger angles) induce higher penetration resistance.

### 3.2 Optimization Outcomes
- **Optimal Geometry:** $H = 3r$, $b = 5r$, and $\alpha = 60^\circ$.
- **Optimal Control:** $V_D = 0.01$ m/s, $V_R = 0$ rpm, $V_E = 0.01$ (normalized expansion), and $L = 3r$ (anchor-cone distance).

## 5 Concluding Remarks
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. Small anchor height and moderate cone apex angles are preferred for low power consumption.
3. Low downward velocity and minimum rotation/expansion velocities contribute to optimal drilling efficiency.
4. Closer anchor-cone distance improves stress relaxation near the cone tip.