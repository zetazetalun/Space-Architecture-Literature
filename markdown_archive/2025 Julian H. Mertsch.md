# A Compact Concrete Mixing System for High Quality Specimen Production in Space: Automated MASON Concrete Mixer

**Authors:** Julian H. Mertsch, Julian T. I. Müller, Stefan Kleszczynski, Bernd Rattenbacher, Martina Schnellenbach-Held

## Abstract
Establishing a sustainable human presence on the Moon and Mars will require the use of locally available resources for construction. A binder material similar to concrete is a promising candidate, provided that its production and performance under reduced gravity can be reliably understood. The development of an automated MASON Concrete Mixer (MCM) prototype is presented. It integrates motorized mixing and programmable process control into the established containment architecture, enabling reproducible specimen production while reducing crew workload. The automated MCM demonstrated reduced variability in tested concrete properties and provides a scalable path to uncrewed missions and future extraterrestrial construction technologies.

## 1. Introduction
Future exploration roadmaps envision a sustained human presence on the Moon and Mars, requiring the use of local resources to produce building materials. A regolith-based binder similar to concrete is a promising candidate for habitats, landing pads, and radiation shielding. Previous microgravity investigations (ConCIM, MICS, BRIC) were limited by hardware constraints, producing low-quality specimens. The first-generation MASON Concrete Mixer (MCM) allowed for safe specimen production aboard the ISS but was fully manual. The current study introduces an automated MCM prototype to ensure reproducibility and suitability for uncrewed missions.

## 2. Development of an Automated Prototype of the MCM
### 2.1. Preliminary Considerations and Requirements
Requirements for the prototype included:
* Automation and standardization of the mixing process.
* Integration with the existing, space-approved MCM architecture.
* Modular structure for future hardware and process adjustments.
* Suitability for laboratory environments and future space adaptation.

### 2.2. Design and Components
* **Mixing Unit:** Consists of two separate drives: a rotary drive for the mixing blade and a linear drive for vertical movement. Both use NEMA 17 stepper motors.
* **Gearbox:** A worm gear (ratio i=13) is used for the rotary drive to increase torque to the required 2 Nm while allowing off-center mounting for syringe access.
* **Frame:** Built from 40x40 light aluminum profiles.
* **Control System:** Controlled by an Arduino microcomputer, with an LCD and push-button interface for human-machine interaction.

### 2.3. Torque Tests and Specifications
Torque tests were performed using an Atlas Copco ETD MT41-250-I06 measuring tool to determine drive requirements.

| Mixture | Aggregate | Mass of Cement | Mass Aggregate | Mass of Water |
| :--- | :--- | :--- | :--- | :--- |
| R | None | 54 g | - | 21.5 g |
| R-SS | CEN standard sand | 17 g | 51 g | 11.5 g |
| R-R | Regolith EAC-1A | 22 g | 44 g | 15.5 g |

**Maximum Determined Torques:**
| Mixture | Dry Mixing (cNm) | Mixing with Water (cNm) |
| :--- | :--- | :--- |
| R | 84.0 | 101.8 |
| R-SS | 111.0 | 112.4 |
| R-R | 44.4 | 90.4 |

## 3. Results and Discussion
Ten concrete samples were produced using the AMCM. After an initial calibration run (R-1), the following nine samples were homogeneous. 
* **Quality:** Specimens produced by the AMCM exhibited uniform bulk density and porosity, with reduced variability compared to manual mixing.
* **Durability:** The carbon mixer blades showed some damage when mixing larger grains (R-SS), suggesting a need for material adjustment or torque monitoring to prevent mechanical failure at torques above 2.3 Nm.
* **Comparison:** AMCM samples showed higher uniformity in compressive strength and porosity compared to manual MCM samples.

## 4. Conclusions
The prototype successfully automated the mixing process, fulfilling the main requirement for uniform sample production. The system is robust and adaptable, serving as a basis for a future space-qualified, fully autonomous lunar version. Further research will focus on mixer blade durability and the automation of water injection and specimen compression.