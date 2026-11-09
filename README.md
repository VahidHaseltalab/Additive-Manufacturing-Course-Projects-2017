# Additive Manufacturing | Selected Course Projects

**CAD/CAM · Computational geometry · Process planning · 3D printing**

A collection of selected academic course projects demonstrating computational approaches to additive manufacturing. Developed using **Rhino 3D**, **Grasshopper**, and, where applicable, **Python** and **Galapagos**. The original demonstrations were published on YouTube in **January 2020** and remain linked here to preserve their original publication dates.

The projects cover three complementary stages of a digital manufacturing workflow: **part orientation**, **slicing and toolpath generation**, and **G-code simulation**.

> **Portfolio note:** These are historical academic project demonstrations, not currently maintained production software. This repository documents the projects and links to the original video demonstrations. Source code and Grasshopper definitions are not included.

## Projects

### 1. Build Orientation Optimization for FDM Printing

**Rhino 3D · Grasshopper · Galapagos | Video published January 12, 2020 | 4:27**

Investigates how part orientation affects support requirements, manufacturing costs, and surface quality in fused deposition modeling (FDM). The demonstration explores the use of the **Galapagos optimization tool in Grasshopper** to search for a suitable printing orientation.

**Engineering focus:** design for additive manufacturing, optimization, part orientation, and printability considerations.

**Original video:** *Orientation optimization for FDM printer*. **Direct YouTube URL pending verification.** [Search YouTube for the original title](https://www.youtube.com/results?search_query=Orientation+optimization+for+FDM+printer+Vahid+Haseltalab)

[Project details](projects/01-build-orientation-optimization.md)

### 2. Inclined Slicer for an FDM Printer

**Rhino 3D · Grasshopper | Video published January 11, 2020 | 1:30**

A prototype slicing workflow for the **BLACKBELT inclined FDM printer**. The original demonstration describes angled slicing, adjustable shell thickness, infill generation at a selected density, and **G-code output**.

**Engineering focus:** computational geometry, nonstandard slicing, manufacturing process planning, and toolpath generation.

[![Watch the inclined slicer demonstration](https://img.youtube.com/vi/m2wUATY2MKM/hqdefault.jpg)](https://www.youtube.com/watch?v=m2wUATY2MKM)

**[Watch the original demonstration on YouTube](https://www.youtube.com/watch?v=m2wUATY2MKM)** · [Project details](projects/02-inclined-slicer.md)

### 3. G-code Simulator in Grasshopper 3D

**Rhino 3D · Grasshopper · Python | Video published January 6, 2020 | 9:09**

Explores the use of **Python within Grasshopper** to simulate the motion and process of a 3D printer from G-code. The demonstration illustrates how a visual programming environment can support the investigation and communication of manufacturing toolpaths.

**Engineering focus:** G-code, toolpath visualization, computational manufacturing, and Python-based simulation.

[![Watch the G-code simulation demonstration](https://img.youtube.com/vi/lSWfTrf4IHk/hqdefault.jpg)](https://www.youtube.com/watch?v=lSWfTrf4IHk)

**[Watch the original demonstration on YouTube](https://www.youtube.com/watch?v=lSWfTrf4IHk)** · [Project details](projects/03-gcode-simulator.md)

## Shared workflow

| Stage | Project | Engineering question |
|:--|:--|:--|
| **Part preparation** | Build orientation optimization | How should a part be oriented for printing? |
| **Process planning** | Inclined slicer | How can angled layers, shells, infill, and G-code be generated? |
| **Process visualization** | G-code simulator | How can a toolpath be visualized before or alongside fabrication? |

These projects are presented as separate course exercises. They are **not** represented as a single integrated, validated software system.

## Author

**Vahid Haseltalab, PhD**  
[GitHub profile](https://github.com/VahidHaseltalab) · [ORCID](https://orcid.org/0000-0003-2878-2203)

## Project status and attribution

- **Demonstration dates:** January 2020. They refer to the dates of the existing YouTube uploads, not the date this GitHub repository is created.
- **Code and CAD assets:** Not provided in this documentation-only repository.
- **Video ownership:** All video links point to the existing videos on YouTube. Video files are not redistributed here.
- **Documentation:** Summaries are based on the original video titles and descriptions. Additional implementation details should be checked against the demonstrations before being claimed.
