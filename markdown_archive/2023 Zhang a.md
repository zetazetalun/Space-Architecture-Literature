# Multi-objective design optimization of clam-inspired drilling into the lunar regolith

**Authors:** Liang Zhang, Lei Wang, Quan Sun, Jesus Badal, Qiushi Chen  
**Journal:** Acta Geotechnica (2024) 19:1379–1396  
**Published:** 26 November 2023  

## Abstract
Characterization of the lunar regolith is critical for the extraction and utilization of in situ resources for building a permanent base on the Moon. This paper presents a two-stage multi-objective optimization design framework for a clam-inspired drill. Using Discrete Element Method (DEM) simulations calibrated with lunar simulant LHS-1, the study optimizes drill geometry and controlling strategies to minimize construction cost and power consumption while maximizing effectiveness and efficiency.

## 1 Introduction
Lunar regolith has great prospects for construction and habitation on the Moon. Characterization through drilling is crucial. Bio-inspired strategies, such as clam-inspired drilling, offer highly efficient, low-cost, and sustainable designs. The clam-inspired mechanism involves shell valves and a stretchable foot, utilizing cone penetration, anchor expansion, and self-penetration phases.

## 2 Methodology
- **Numerical Model:** 3D DEM-based program Particle Flow Code (PFC3D) v7.0.
- **Simulant:** Lunar highlands simulant (LHS-1).
- **Geometry Optimization (Stage 1):** Parameters include anchor height (H), anchor shape (b), and cone apex angle (alpha).
- **Control Optimization (Stage 2):** Parameters include downward velocity (VD), rotation velocity (VR), expansion velocity (VE), and anchor-cone distance (L).

### Table 1: Input Parameters for DEM
| Parameter | Value |
|---|---|
| Particle density | 2720 kg/m³ |
| Porosity | 0.45 |
| Particle radius | 0.004 m |
| Gravity | 1.625 m/s² |

## 3 Results: Geometry Optimization
- **Pareto Front:** Identified conflicting objectives between construction cost and power consumption.
- **Optimal Geometry:** Knee point identified at H=3r (short anchor), b=5r (arc-shaped profile), and alpha=60 degrees (moderate cone angle).
- **Findings:** Cylinder-shaped anchors and sharp tips reduce penetration resistance by effectively relaxing stress near the cone tip.

## 4 Results: Controlling Strategies
- **Effectiveness (E1):** Power reduction for overcoming resistance.
- **Efficiency (E2):** Power reduction normalized by additional expansion/rotation efforts.
- **Optimal Control:** VD = 0.01 m/s, VR = 0, VE = 0.01 m/s, L = 3r. Lower downward velocities provide more time for regolith stress relaxation.

## 5 Concluding Remarks
1. Cylinder-shaped anchors and sharp tips effectively reduce penetration resistance.
2. Optimal drill geometry utilizes arc-shaped anchors with minimal height.
3. Low downward/rotation velocities and closer anchor-cone distances maximize efficiency.
4. The framework provides a guide for designing bio-inspired tools for extraterrestrial exploration and construction.