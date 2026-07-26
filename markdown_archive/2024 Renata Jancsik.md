# Flow Dynamics of Lunar Regolith For In-Situ Utilization and Transportation

**Authors:** Renata Jancsik, David Canales, Yizhou Jiang  
**Affiliation:** Embry-Riddle Aeronautical University

## Abstract
Lunar regolith, the loose, heterogeneous material covering the Moon’s surface, presents both challenges and opportunities for extraterrestrial construction. This research aims to study the fundamental mechanics of Lunar regolith flow using ANSYS Rocky. The focus lies in analyzing regolith simulant behavior through pipe-like structures under varying physical environments such as different gravitational forces. Simulations will be validated with physical experiments, demonstrating Rocky’s efficacy in simulating particle motion on the Moon. This marks an initial step toward achieving space-based in-situ utilization and transportation.

## I. Introduction
The exploration and utilization of extraterrestrial resources are paramount for establishing sustainable human habitats. Recent missions, like the IM-1 Lunar Lander (Odysseus), highlight challenges posed by the powdery and unstable properties of Lunar regolith. Manufacturing landing pads is necessary to conduct safe landings and launches. By employing in-situ resource utilization (ISRU) techniques, it is possible to create structures like roads and radiation shelters efficiently and autonomously using regolith.

## II. Particle Modeling/Properties
To achieve reliable results without wasting physical materials, ANSYS Rocky, a discrete element modeling (DEM) software, is used. The software models particle-particle interactions by following Newton’s second law of motion for translation and rotation.

### A. Volcanic Ash Properties
Volcanic ash from Mt. St. Helens was chosen as a comparison material due to mineral similarities with lunar regolith.

**Table 1: Mineral composition comparison of volcanic ash and Lunar regolith**

| Mineral | Volcanic Ash | Lunar Regolith |
| :--- | :--- | :--- |
| SiO₂ | 65% | 43% |
| Al₂O₃ | 16% | 18% |
| FeO | 5% | 12% |
| CaO | 4% | 11.7% |
| MgO | 2% | 10.3% |

### B. Lunar Regolith Simulant: JSC-1A Properties
JSC-1A is specifically engineered to replicate lunar mare soil. Simulations utilized CAD data from ~14,000 particles studied via X-ray micro-CT scans.

## III. Static Angle of Repose Test
The angle of repose (SAOR) helps characterize how material settles before sintering. Lower repose angles indicate greater flow-ability.

**Table 2: Carr classification of flowability of powder based on repose angle**

| Description | Repose Angle |
| :--- | :--- |
| Very free-flowing | <30° |
| Free flowing | 30–38° |
| Fair to passable flow | 38–45° |
| Cohesive | 45–55° |
| Very cohesive (non-flowing) | >55° |

### Results: SAOR Simulations & Experiments
- **Volcanic Ash (Simulated):** ~12°, categorized as very free-flowing.
- **JSC-1A (Simulated):** ~4°, categorized as very free-flowing.
- **JSC-1A (Physical):** ~6°, demonstrating close alignment with simulated results.

## IV. Sintered Regolith Flow
Direct sintering of Lunar regolith eliminates the need for Earth-transported binders. Smoothed Particle Hydrodynamics (SPH) was used to model the flow of molten "black glass" regolith from a hopper.

- **Earth’s Gravity:** Particles exhibit uniform downward movement with fast, consistent flow.
- **Lunar Gravity:** Particles fall more slowly, resulting in more gradual, cohesive movement and stronger adhesion to container walls due to lower gravitational forces competing with friction.

## V. Conclusion
Volcanic ash and JSC-1A serve as valuable analogs for understanding lunar material behavior. Sintered regolith shows potential for construction in lunar environments. Precision modeling in ANSYS Rocky allows for the optimization of material handling and additive manufacturing processes in vacuum and low-gravity conditions.