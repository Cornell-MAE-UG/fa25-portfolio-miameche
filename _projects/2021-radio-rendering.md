---
layout: project
title: MAE 3270 Torque Wrench
description: Advanced CAD Project
technologies: [Autodesk Fusion, ANSYS, Granta Material Database]
image: /assets/images/radio-machine-cad.jpg
---

Final Project for MAE 3270: Mechanics of Materials

For my Mechanicals of Materials class, I designed an instrumented torque-wrench capable of measuring torque using strain gauges bonded to the wrench handle. I began with a baseline design and performed hand calculations to estimate bending stresses, strains at the gauge location, and global deflection under the rated 600 in-lbf torque. I then built a finite element model in ANSYS to compare these analytical predictions with a more realistic 3D simulation. After evaluating the limitations of the baseline geometry, I iterated the design by selecting an appropriate material, adjusting key dimensions, and incorporating features to improve sensitivity while meeting safety requirements for yield, fatigue, and fracture. I created a CAD model of the final design, imported it into ANSYS, and performed mesh refinement and full stress/strain analysis. Using the FEM strain results, I computed the wrench’s electrical sensitivity in mV/V and confirmed that the final design satisfied all specification constraints.

Click [here]({{ "/assets/Part2MaterialsLastHW.pdf" | relative_url }}) for my final project write-up.
