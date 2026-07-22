# Building Information Modeling (BIM) Workflows for Construction Sequencing & 4D-Planning of 3D-Printed ISRU Surface Habitats

**M. Yashar, P. Michealsen, B. Hammond, J. Alvizar, C. Ciardullo, M. Morris, R. Pailes-Friedman, G. Bell, R. Tucker, T. Shen, S. Austin, L. LeBlanc**

## Abstract
Future autonomously constructed surface habitats on the Moon and Mars will leverage additive manufacturing technologies to create airtight and durable structures. Building Information Modeling (BIM) workflows present significant value in the design and engineering of space systems, particularly habitat facilities that include pre-integrated hardware (ECLS, airlocks, suitports). This paper defines the landscape of BIM use for robotic deployment of space habitats and describes project contributions to BIM workflows for ISRU surface habitats.

## Introduction
Robotic precursor missions will autonomously construct surface infrastructure prior to crew arrival. Construction sequences must consider site conditions, raw material quantities for ISRU, feedstock storage, and access to power. In SEArch+/Apis Cor’s NASA Phase 3 Centennial Challenge submission, the team merged BIM workflows between Rhino/Grasshopper, Revit, Navisworks, and proprietary slicer software to estimate completion time and material quantities.

## Uses of BIM in AEC
BIM enables holistic collection of linked building information, allowing metadata embedding (material properties, quantity takeoff, assembly information, and construction timing) within 3D components. Interoperability is achieved through the Industry Foundation Classes (IFC) standard.

## BIM for Manufacturing and 3D-Printing
BIM software converts 3D geometry into CNC codes (G-code) for additive deposition. Workflows from BIM to automated additive construction mark a leap in efficiencies, integrating MEP elements and materials schedules into the manufacturing sequence. 

## NASA’s Centennial Challenge: Mars X-House
SEArch+ / Apis Cor won first place in the Virtual Construction (BIM) Level 2 (100% Design) within NASA’s Phase 3 Challenge. 

### Requirements:
- Pressure-retaining living space: at least 93 m².
- Support for four astronauts for one year.
- BIM model and 4D construction sequence simulating autonomous activities (machinery, 3D printing, component emplacement).
- Mandatory elements: suit hatch, view port, rover hatch, comms/power penetrations.

### Scoring Rubric (Table 1):
| Scoring Area | Requirements | Points |
|---|---|---|
| Completeness of 3D Model | a) Element Level of Development; b) System Information | 125; 125 |
| BIM Use Functionality | a) Layout/Efficiency; b) Constructability/Robustness | 250; 250 |
| Aesthetic Representation | Aesthetic Representation | 250 |
| 4D Model Realism (Bonus) | a) Construction Sequencing; b) Material & Equipment Flow; c) Virtual Mockup | 100; 70; 30 |
| **Total** | | **1000 + 200 bonus** |

## Software Workflow
- **Rhino/Grasshopper**: Parametric modeling of the regolith structural shell.
- **Autodesk Revit**: Interior design and assignment of material families.
- **Autodesk Navisworks**: 4D construction sequence generation, assigning elements to schedule activities based on printer trajectory speed and volume.

## Conclusion
Autonomous construction requires precise coordination between 3D-printing systems, ISRU machinery, and robotic assembly of hard-shell sub-systems (ECLS, airlocks). A dynamic BIM framework updated in real-time is critical for human-machine collaboration and error correction during construction.