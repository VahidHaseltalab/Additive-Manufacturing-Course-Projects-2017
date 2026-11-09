# Additive Manufacturing | MSc Course Project Portfolio

**Selected projects from MSc studies at Middle East Technical University (METU), Ankara, Türkiye (2015–2018)**

This repository documents three early academic projects in **CAD/CAM, computational geometry, and additive manufacturing**. Developed as part of graduate coursework and related exploratory work, these projects investigate build orientation optimization, inclined slicing, and the simulation of 3D printing toolpaths using **Rhino 3D, Grasshopper, Galapagos, and Python**.

The original demonstration videos were uploaded to **YouTube in January 2020, approximately six years ago**. The links below point to those original uploads to preserve their publication dates and provide a record of the work completed during the MSc period.

> **Archive note:** This is a portfolio of historical MSc-era projects, not a newly developed or actively maintained software suite. The GitHub repository documents the work today, while the linked YouTube videos retain their original 2020 upload dates. The complete Grasshopper project definitions are not included here. A related Python script for the G-code simulator is available in a separate GitHub repository linked below.

## Project demonstrations

### 1. Build Orientation Optimization for FDM Printing

**Tools:** Rhino 3D, Grasshopper, Galapagos  
**Original video:** January 12, 2020 | 4:27

Explores the selection of a suitable build orientation for fused deposition modeling (FDM) using **Galapagos**, the evolutionary optimization component of Grasshopper. The project considers how orientation can affect support structures, printing cost, and surface quality.

[![Build orientation optimization demonstration](https://img.youtube.com/vi/8rouahb1yqI/hqdefault.jpg)](https://www.youtube.com/watch?v=8rouahb1yqI)

**[Watch the original video on YouTube](https://www.youtube.com/watch?v=8rouahb1yqI)** | [Read project details](projects/01-build-orientation-optimization.md)

### 2. Inclined Slicer for an FDM Printer

**Tools:** Rhino 3D, Grasshopper  
**Original video:** January 11, 2020 | 1:30

Presents a prototype slicer developed for the **BLACKBELT inclined FDM printer**. The demonstration describes slicing at an inclined angle, generating shells with adjustable thickness, creating infill, and exporting G-code for manufacturing.

[![Inclined slicer demonstration](https://img.youtube.com/vi/m2wUATY2MKM/hqdefault.jpg)](https://www.youtube.com/watch?v=m2wUATY2MKM)

**[Watch the original video on YouTube](https://www.youtube.com/watch?v=m2wUATY2MKM)** | [Read project details](projects/02-inclined-slicer.md)

### 3. G-code Simulator in Grasshopper 3D

**Tools:** Grasshopper 3D, Python  
**Original video:** January 6, 2020 | 9:09

Explores **Python-driven G-code interpretation and simulation within Rhino and Grasshopper**. The original video demonstrates the visualization of manufacturing toolpaths. Related source code extends the work to a **hybrid additive and subtractive manufacturing simulation**, with separate motion handling for printing and machining, virtual machine axis updates, and geometric representations of material addition and removal.

[![G-code simulator demonstration](https://img.youtube.com/vi/lSWfTrf4IHk/hqdefault.jpg)](https://www.youtube.com/watch?v=lSWfTrf4IHk)

**[Watch the original video on YouTube](https://www.youtube.com/watch?v=lSWfTrf4IHk)** | **[Explore the Python code and hybrid simulation](https://github.com/VahidHaseltalab/grasshopper-3D-simulation)** | [Read project details](projects/03-gcode-simulator.md)

The linked code is a historical Grasshopper Python script, not a standalone application or a complete runnable project package.

## Technical themes

| Project | Primary focus | Relevant skills |
| --- | --- | --- |
| Build orientation optimization | Design for additive manufacturing | Parametric modeling, evolutionary optimization |
| Inclined slicer | Slicing and process planning | Computational geometry, shell and infill generation, G-code |
| G-code simulator | G-code interpretation and hybrid process simulation | Python, Grasshopper, virtual machine motion, geometry operations |

Although these projects address complementary stages of an additive manufacturing workflow, they were developed as **separate academic exercises** and are not presented as a validated integrated software system.

## About

**Vahid Haseltalab**  
MSc in Mechanical Engineering, Middle East Technical University (2018)

[GitHub](https://github.com/VahidHaseltalab) | [ORCID](https://orcid.org/0000-0003-2878-2203)

*Project period: MSc studies, 2015–2018. Original demonstration uploads: January 2020.*
