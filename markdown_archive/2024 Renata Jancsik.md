# Flow Dynamics of Lunar Regolith For In-Situ Utilization and Transportation

**Authors:** Renata Jancsik, David Canales, Yizhou Jiang  
**Affiliation:** Embry-Riddle Aeronautical University

## Abstract
Lunar regolith, the loose, heterogeneous material covering the Moon’s surface, presents both challenges and opportunities for extraterrestrial construction. This research aims to study the fundamental mechanics of Lunar regolith flow using ANSYS Rocky. Renowned for simulating bulk materials with intricate particle shapes and diverse sizes, ANSYS Rocky models particle-particle interactions accurately. The focus lies in analyzing regolith simulant behavior through pipe-like structures under varying physical environments such as different gravitational forces. Simulations will be validated with physical experiments, demonstrating Rocky’s efficacy in simulating particle motion on the Moon. This marks an initial step toward achieving space-based in-situ utilization and transportation.

## I. Introduction
The exploration and utilization of extraterrestrial resources have emerged as paramount objectives in contemporary space endeavors, particularly in the context of establishing sustainable human habitats beyond Earth. In response to the growing interest of the Moon’s Southern regions, manufacturing landing pads is necessary to conduct safe landings and launches from the Lunar surface. By employing in-situ resource utilization (ISRU) techniques, specifically in situ manufacturing with regolith, it is possible to create these structures efficiently and autonomously. Beyond landing pads, new manufacturing technology may be applied to build other essential structures through ISRU, such as roads and radiation shelters.

## II. Particle Modeling/Properties
The primary objective of this investigation is to employ ANSYS Rocky, a discrete element modeling (DEM) particle simulation software. To bridge the gap between simulated and experimental results, volcanic ash and the Lunar regolith simulant JSC-1A are modeled. 

### A. Volcanic Ash Properties
Volcanic ash from Mt. St. Helens is chosen due to similarities in mineral and chemical compositions to lunar regolith, primarily silicates.

**Table 1: Mineral composition comparison of volcanic ash and Lunar regolith**

| Mineral | Volcanic Ash | Lunar Regolith |
| :--- | :--- | :--- |
| SiO2 | 65% | 43% |
| Al2O3 | 16% | 18% |
| FeO | 5% | 12% |
| CaO | 4% | 11.7% |
| MgO | 2% | 10.3% |

### B. Lunar Regolith Simulant: JSC-1A Properties
JSC-1A is a Lunar regolith simulant derived from basaltic volcanic ash, designed to closely replicate the composition and characteristics of Lunar mare soil, including its chemical composition, mineralogy, particle size distribution, specific gravity, and cohesion.

## III. Static Angle of Repose Test
The angle of repose is the maximum angle at which grains can remain stable without shifting. Understanding this is essential for assessing the suitability of materials for applications like additive manufacturing.

**Table 2: Carr classification of flowability of powder based on repose angle**

| Description | Repose Angle |
| :--- | :--- |
| Very free-flowing | <30° |
| Free flowing | 30–38° |
| Fair to passable flow | 38–45° |
| Cohesive | 45–55° |
| Very cohesive (non-flowing) | >55° |

### A. SAOR Results
- **Volcanic Ash (Simulation):** ~12 degrees (Very free-flowing).
- **JSC-1A (Simulation):** ~4 degrees (Very free-flowing).
- **JSC-1A (Physical Experiment):** ~6 degrees.

## IV. Sintered Regolith Flow
Direct sintering of Lunar regolith eliminates the dependency on additional binder materials transported from Earth. Sintered Lunar regolith, often called "black glass," can be shaped into durable building bricks. 

Smooth particle hydrodynamics (SPH) was used to model the flow of molten regolith. Sintered regolith was modeled with a density of 2850 kg/m³, a viscosity of 4 Pa·s, and a kernel size of 1 mm.

### Findings on Lunar Gravity
In Lunar gravity, particles fall more slowly than on Earth, resulting in a more gradual flow. Particles exhibit stronger adhesion to container walls due to lower gravitational forces competing with frictional forces, leading to significant boundary layer flow resistance. This can result in less compact material deposition in the receiving area.

## V. Conclusion
This research demonstrates the importance of precise modeling for ISRU construction. Tests like the static angle of repose help characterize the flow and stability of particles under varying conditions. Sintered regolith demonstrates potential for construction in both Lunar and Earth atmospheres. Simulations conducted in Lunar vacuum conditions highlight differences in material properties when exposed to the Moon’s gravity compared to Earth’s, providing critical insights into material behavior during the sintering process.