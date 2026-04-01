# Role of Cyber-Physical Testing in Developing Resilient Extraterrestrial Habitats

**Authors:** Amin Maghareh, Ali Lenjani, Murali Krishnan, Shirley Dyke, and Ilias Bilionis  
**Affiliation:** School of Mechanical Engineering, Purdue University, West Lafayette, IN 47906  
**Publication:** Earth and Space 2021, ASCE

## Abstract
Extraterrestrial long-term habitat systems require groundbreaking technological advances to overcome the extreme demands introduced by isolation and challenging environments. A habitat system must operate as intended under continuous disruptive conditions. This study highlights the importance of system resilience and cyber-physical testing to address the grand challenge of developing habitat systems.

## Introduction
The quest for permanent settlements on the Moon and Mars requires habitats that can withstand wild temperature fluctuations, galactic cosmic rays, destructive dust, meteoroid impacts, vibrations, and solar particle events. The paper argues that current reliability-based design philosophies (focused on probability of meeting marginal values) are insufficient for the complex, tightly-coupled nature of space habitats.

## Environmental Conditions
Extraterrestrial environments differ significantly from Earth. Key physical characteristics are compared in the table below:

### Table 1. Physical comparison of Earth, the moon, and Mars.
| Property | Earth | Moon | Mars |
| :--- | :--- | :--- | :--- |
| Mass (kg) | 5.97 × 10²⁴ | 7.35 × 10²² | 6.42 × 10²³ |
| Spherical radius (km) | 6378 | 1738 | 3393 |
| Equatorial gravity (m/sec²) | 9.80 | 1.62 | 3.71 |
| Temperature extremes (°C) | -89 to 58 | -233 to 123 | -153 to 20 |
| Atmospheric pressure (kPa) | 101 | 3 × 10⁻¹² | 0.4 to 0.87 |
| Surface magnetic field (G) | 0.31 | ≤ 2 × 10⁻³ | ≤ 5 × 10⁻⁴ |
| Sidereal rotation (day) | 0.997 | 27.322 | 1.03 |

### Environmental Hazards
- **Radiation:** High-energy galactic cosmic rays (GCR) and solar particle events (SPE).
- **Thermal Fluctuations:** Transitions up to 5 °C/hr on the Moon can lead to material fatigue.
- **Dust:** Causes malfunction of mechanical/electronic devices and loss of solar power.
- **Seismic Activity:** Moonquakes can last for hours, unlike Earth's minutes-long quakes.

## Resilience and Cyber-Physical Testing
Resilience is defined by three conceptual capacities: **absorptive, restorative, and adaptive**. The paper proposes a control-theoretic approach to design, which includes:
1. **System Plasticity:** Ability to prevent performance loss and diagnose damage.
2. **System Rapidity:** Ability to restore performance in a timely manner.
3. **Lifecycle Cost:** Minimizing the total cost of passive and adaptive controls.

### Cyber-Physical Architecture
Cyber-physical testing (or hybrid simulation) integrates physical testing with computational modeling. This allows researchers to:
- Partition the system into computational domains (well-understood components) and physical domains (novel or complex components).
- Use sensors and actuators at interfaces to enforce boundary conditions.
- Evaluate the dynamic performance of habitats under multi-hazard scenarios without the prohibitive cost of full-scale physical experiments.

## Conclusion
The Resilient ExtraTerrestrial Habitats research institute (RETHi) is developing a platform to validate these models. Cyber-physical testing is essential for examining emergent behaviors in complex habitat systems and ensuring they can function autonomously across various operating modes.