# Laboratory-Scale Distributed Pressure Measurements of Blade Interaction with JSC-1A Lunar Simulant

**Robert H. King and Andrew T. Brewer**

**Abstract:** Because of the requirement for high reliability and very low weight, extraterrestrial excavator blade design for in situ resource utilization (ISRU) must be more precise than for current terrestrial practice. Three-dimensional finite-element and discrete-element models should be employed to enhance the precision of designs. These models require that the pressure distribution across the blade be known; however, this information is not available in the literature. To provide the information, this project measured the pressure distribution on a suite of laboratory-scale blades. The project constructed a suite of laboratory-scale model blades, designed and implemented distributed pressure and total load measurements, developed soil preparation techniques, measured pressure distributions and errors, and created empirical pressure distribution models. The models include: an array of point pressures, a quadratic function, and an exponential function. The work concluded that a V-shaped blade with a tapered curve is the best configuration, and multiple passes of small-depth cuts is the best excavation operating procedure. **DOI: 10.1061/(ASCE)AS.1943-5525.0000224.** © 2013 American Society of Civil Engineers.

**CE Database subject headings:** Lunar materials; Excavation; Space construction; Load factors; Measurement; Simulation.

**Author keywords:** Lunar materials; Excavation; Space construction; Soil-blade interaction; Blade-distributed pressure measurement; Extraterrestrial excavation.

## Introduction

If outposts are developed on extraterrestrial bodies, such as the moon, several soil handling tasks are required, such as creating roads and landing sites (Mueller and King 2007). Outpost development requires a robotic machine, like the National Aeronautics and Space Administration prototype shown in Fig. 1, to build berms, grade and compact roads, excavate foundations, smooth landing pads, and excavate trenches for utilities (Mueller et al. 2009). Robotic excavators must be designed to withstand the stresses of excavation without failing. Relatively large design factors are applied to over-design terrestrial excavators for operator abuse, long life, and varied conditions, resulting in equipment power and sizes that range from 13 to 382 kW and 1,558 to 84,980 kg. Launch costs of such large equipment are prohibitive, and therefore precise design must take the place of design factors. Precise design begins with analysis of the pressures on the blade. If excavation pressures are known, finite-element and discrete-element models can be used to calculate stresses and displacement in the frame and joints, determine tractive requirements, size motors, and provide data for trade studies.

Overdesign would consider a worst case scenario where the corner of the blade impacts a large rock, which might be buried and unseen (Fig. 1). Finite-element analysis (FEA) for this scenario where a 22,241-N point load was applied to simulate the corner of the blade hitting a large rock buried in soil at full speed resulted in a factor of safety of 0.013 for the pathfinder design shown in Fig. 1. The FEA was verified when the corner of the blade hit a wet pile of sand when the vehicle was traveling at full speed and the blade support buckled.

A sophisticated robotic excavator would sense the increased stress from a worst case scenario and react by pulling back quickly. Consequently, a design should consider the normal operating load as well as the worst case scenario. The average operating load can be simulated with traditional models (King et al. 2011). However, these models are two-dimensional, or if they are three-dimensional, they provide only average uniform pressure distributions over the blade surface, which doesn't accurately simulate practice or take full advantage of the capability of the FEA software (King et al. 2010). Nonuniform load distribution is typical of excavation practice, because soil doesn't press against the upper corners, the surcharge shape is curved, the middle of the blade pushes the most soil, and the surcharge extends beyond the edge of the blade (Fig. 2). This project measured nonuniform pressures on laboratory-scale blades and developed load models that will improve the accuracy of extraterrestrial excavator blade design.

## Measurements

Pressure was measured on a suite of laboratory-scale straight and V-shaped blades (Fig. 3) (Brewer 2011). The straight blade simulates the LANCE-type blade. The V-shaped blade design may be better for extraterrestrial application, because it minimizes the load during excavation by diverting the soil to either side of the blade. Two sets of straight blades compare blade widths (20.32, 25.40, and 30.48 cm) and face curvature, while the V-blades compare the blade shapes as well as angles (15, 30, and 45°). The following were varied by evaluating change in one variable at a time while keeping all others at a base configuration: the material being excavated, the cutting depth, the cutting angle, the rake angle, and the blade width (Table 1). Additional tests were performed to compare straight and curved blades (Table 2). Some measurements were made with a square rod instead of a blade in order to compare with previous measurements by Gefreh (2008) to evaluate repeatability and error.

The blades were mounted in the Colorado School of Mines (CSM) soil excavation measurement apparatus (Fig. 4), where a soil tray moves under an excavation tool (Johnson and King 2010). The National Instruments PXI data acquisition (DAQ) and control system measures the velocity and horizontal and vertical forces automatically, maintains constant velocity, and stops the test automatically at the end of travel.

The traditional test bed DAQ measures total load on the cutting tool, and therefore a Tekscan I-Scan universal serial bus (USB) evolution single-input pressure mapping system (Tekscan 2009) was added to measure distributed pressure over the surface of the tool. The system consists of a Model 6300 thin-film resistive sensor and a USB computer interface with data acquisition and analysis software. The sensor was attached to the face of the blade being tested, and the USB interface was mounted to the outer carriage (Fig. 5). This system is typically used for analyzing the contacts between two surfaces that form a seal and have never been applied to small-scale excavation pressure measurements prior to these tests.

The thin-film resistive sensor has an active measurement area of 26.42 x 3.35 cm, a spatial resolution of 25.8 sensing cells (sensels) (per cm²), a maximum sampling rate of 100 Hz, and a pressure range of 0.00–68.95 kPa that can be adjusted for increased resolution. 

### Table 1. Base Configuration and Range for Test Sets by Variable
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | JSC-1A, Ottawa Sand |
| Cutting depth (cm) | 0.635 | 0.127–0.635 (0.127 increments) |
| Rake angle (degrees) | 0 | 0, 8, 12.5 |
| Blade angle (degrees) | 0 | 0, 15, 30, 45 |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Flat | Flat, curved |

### Table 2. Base Configuration and Range for Additional Curved Blade Test Sets
| Variable | Base | Range |
| :--- | :--- | :--- |
| Material | JSC-1A | — |
| Cutting depth (cm) | 0.635 cm | 0.127–0.635 (0.127 increments) |
| Rake angle | — | — |
| Blade angle (degrees)| 0 | — |
| Blade width (cm) | 30.48 | 20.32, 25.40, 30.48 |
| Blade curvature | Curved | — |

## Soil Properties

Two soils were tested: Ottawa Sand and JSC-1A Lunar Soil Simulant. Ottawa Sand was chosen as a base for comparison with tests performed by Gefreh (2008). Ottawa Sand is a pure silicate with a very uniform grain size and subangular grains. The grain distribution and subangular particles make it resistant to settling and compaction, which enhances test repeatability. Ottawa Sand has an internal angle of friction of 33° and a cohesion value of 3.520 kPa (King and van Susante 2007).

JSC-1A mimics the material properties of lunar regolith. It is made from crushed basalt, and therefore the particles are very angular, and the particle size distribution is much more dispersed than Ottawa Sand. JSC-1A is denser than Ottawa Sand. The internal angle of friction, cohesion, external angle of friction, and adhesion are 37°, 1.793 kPa, 23°, and 39 Pa, respectively (King and van Susante 2007). These characteristics make the simulant highly prone to settling and compaction, similar to lunar soil (Carrier et al. 1991). Therefore, soil preparation prior to each test is extremely important.

## Calibration

Both the vertical and horizontal load cells were calibrated with hanging precision weights at three different times during the project: at the outset of the project, after a failure of the horizontal load cell when the 222-N vertical load cell was used, and after the horizontal load cell and amplifier were replaced. The calibration relationships are summarized in Table 3.

### Table 3. Summary of Calibration Relationships
| Relationship | First calibration | Second calibration | Third calibration |
| :--- | :--- | :--- | :--- |
| Horizontal calibration (N) | F = 36.532V - 27.224 | F = 79.676V - 270.61 | F = 38.433V - 37.429 |
| Horizontal coupling (V) | V = {0.0012F + 5.8603 if F < 0; -0.0016F + 5.8565 if F > 0} | Not applicable | V = {-0.0002F + 5.6329 if F < 0; -0.0007F + 5.6263 if F > 0} |
| Vertical calibration (N) | F = -66.767V + 394.18 | Not applicable | F = -76.737V + 424.63 |
| Vertical coupling (V) | Not measured | Not applicable | V = -0.00002F + 0.9973 F < 0 |

### Table 4. Tekscan Sensor Calibration Constants
| Sensor | Scale Factor A | Exponent B |
| :--- | :--- | :--- |
| 1 | 0.0467 | 0.692 |
| 2 | 0.0347 | 0.703 |

## Measurement Procedure

The testing procedure was designed to reduce error while performing the 250 tests as quickly and efficiently as possible. The soil was prepared in the same fashion for both Ottawa Sand and JSC-1A Simulant in order to reduce compaction that would increase after each test and greatly affect the measured forces by raking the soil with a hand-held garden claw backward and forward. The soil was leveled by mounting a plexi-glass panel and moving the tray under the panel. The panel was mounted at the same height for every test, ensuring the same average density and average compaction for all tests.

The Tekscan sensor was attached to the blade face with removable spray adhesive to facilitate mounting on a series of blades... 

## Results

Fig. 6 presents a typical graph that compares the total load measured by the Tekscan sensor and the load cell. Results from all of the scenarios are presented in Brewer (2011). The results from the Tekscan sensor and the load cells are within the maximum expected error.

The average load versus cut depth results for flat and curved blades can be approximated with a second-order polynomial. Because high loads mean a stronger and heavier machine with larger motors requiring higher power, lightweight machines for extraterrestrial application should excavate thin cuts and take multiple passes if necessary.

The data suggest that wider blades are preferred, because the increase in force is the smallest going from the 25.40-cm blade to the 30.48-cm blade. However, wider blades increase the weight of extraterrestrial machines... Consequently, the width should be limited to that necessary to cut clearance for the machine to travel behind the blade.

Higher rake angles reduce the excavation forces. This can be achieved practically with a curved blade. The excavation width decreases as the angle increases; therefore, longer blades are needed at higher angles to cut clearance for the machine.

## Discussion

The cutting depth precision was limited to about a one-quarter turn of the height adjustment rod. This error is equivalent to ±0.03 cm.

An air bubble that measured 1.35 cm from top to bottom at 33 s was caused by bending the sensor to fit the model blade faces. It occurred on all blade geometries. As the surcharge climbed on the blade, the air bubble was pushed toward the top of the sensing area causing pressures to accumulate along the top edge and to lessen under the bubble. 

### Table 5. Square Rod Force Result Comparison in Ottawa Sand
| Depth (cm) | Test | Average force (N) | Difference in force (N) | Standard deviation of force (N) |
| :--- | :--- | :--- | :--- | :--- |
| 0.6350 | Brewer | 0.1266 | 0.1573 | 0.2223 |
| | Gefreh | 0.2839 | | 0.0237 |
| 2.5400 | Brewer | 0.6519 | 0.9663 | 0.2561 |
| | Gefreh | 1.6182 | | 0.0867 |
| 3.8100 | Brewer | 3.5295 | 0.1846 | 0.3432 |
| | Gefreh | 3.3449 | | 0.1331 |

### Table 6. Square Rod Force Result Comparison in JSC-1A Simulant
| Depth (cm) | Test | Average force (N) | Difference in force (N) | Standard deviation of force (N) |
| :--- | :--- | :--- | :--- | :--- |
| 0.6350 | Brewer | 0.5487 | 0.1273 | 0.1354 |
| | Gefreh | 0.4214 | | 0.0474 |
| 1.2700 | Brewer | 0.7513 | 0.0853 | 0.1300 |
| | Gefreh | 0.8366 | | 0.0589 |
| 3.8100 | Brewer | 2.7030 | 3.0939 | 0.3425 |
| | Gefreh | 5.7969 | | 0.3352 |

## Distributed Pressure Models

The distributed pressure models were developed in Mathematica using the least-squares approach for an average of 25 base tests at 33 s, when the surcharge reaches the top of the sensor. It is expected that extraterrestrial robotic equipment control would limit operations to that scenario. Three types of distributed pressure models were developed: direct input to an FEA model of an array of point pressures, a quadratic model specifically for input into the SolidWorks Simulation FEA distributed pressure option, and an exponential model for comparison with the quadratic model, as well as for input into other FEA programs.

The quadratic pressure model with a target load of 4.74 N is of the form:
`Psurcharge = 0.42796 - 0.06647x² + 0.25170x - 0.00854xy - 0.00194y + 0.00187y²`
`Pcut = 0.46`
where Psurcharge and Pcut = pressures in kilopascals, x = surcharge height in centimeters... and y = distance along the blade width in centimeters.

## Conclusions and Recommendations

Considering the errors in measurement, the average pressure and load cell data are in agreement. The measurements showed that a V-shaped blade with an angle of 30° is the best choice, and the blade face of the excavator should be curved to minimize the cutting forces. These tests also suggest that multiple passes of small-depth cuts are the best excavation operating procedure to maintain low force and low power with a light-weight machine. The weight of the excavator blade can be minimized by employing a tapered curve along the blade and removing excess material from the support members.

Future work could generate distributed pressure models for the remaining test scenarios and perform additional analyses with the data collected to develop models that predict effects of variations in cutting depth, blade width, blade shape, and rake angle. This work should also include development of a time-dependent model to assess the effects of the rising surcharge pile. Further work is recommended to determine if the small-scale pressures can be scaled up to larger blades. Work should also be done to evaluate a range of extraterrestrial environmental conditions including low gravity, partial vacuum, extreme temperatures, and soil simulants.