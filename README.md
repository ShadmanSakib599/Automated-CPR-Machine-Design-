# Automated CPR Machine Design

**Please refer to the PDF report included in this repository for full details.**

This project presents the design, modelling, and documentation of an **automated CPR (Cardiopulmonary Resuscitation) machine** intended to provide consistent, reliable chest compressions in emergency or clinical settings.

---

## Project Overview

The automated CPR machine is designed to deliver mechanical chest compressions in accordance with standard CPR guidelines, reducing fatigue and human-error during prolonged resuscitation. Key objectives include:

- Mechanically replicate effective chest compression depth and rate.  
- Ensure the design is safe, reliable, and adaptable to different patient sizes.  
- Facilitate easy integration into emergency care or mobile environments.  
- Provide full design documentation (CAD, schematics, drawing) to support prototyping.

---

## Repository Contents

Below is a summary of the files included in this repository:

| File name                         | Type | Description |
|----------------------------------|------|-------------|
| `Automated_CPR_Machine_Assembly.step` | STEP | Complete CAD model of the machine assembly for integration and simulation. |
| `Automated_CPR_Machine_Assembly.stl`  | STL  | Mesh version of the assembly suitable for rapid prototyping or 3D printing. |
| `CPR_Machine_Frame.step`            | STEP | Structural frame component for the machine. |
| `CPR_Machine_Frame.stl`             | STL  | Mesh version of the frame component. |
| `Actuation_Module.step`             | STEP | Actuator, linkage and mechanism CAD for the compression module. |
| `Actuation_Module.stl`              | STL  | Mesh version of the actuation module. |
| `Technical_Drawing_CPR_Machine.pdf` | PDF  | Technical drawing including dimensions, tolerances, mounting, and interface details. |

*(Adjust or rename files as appropriate if there are differences)*

---

## Design Goals & Constraints

### Loads & Functional Requirements
- Achieve standard chest compression depth (e.g., ~5-6 cm) and rate (100-120 compressions/min) per current guidelines.  
- Interface with patient chest and secure mounting base for stability.  
- Accommodate variability in patient size and chest compliance.

### Performance Targets
- Consistent compression depth and force throughout operation.  
- Maintain structural integrity and mechanism repeatability under repeated cycles.  
- Minimise device footprint and weight where possible for portability.

### Manufacturing & Integration
- Design components suitable for CNC machining, sheet-metal fabrication, or additive manufacturing.  
- Provide mount interfaces for power, control electronics, actuators, and patient contact surfaces.  
- Incorporate safety features (end stops, over-travel protection, quick release for emergency hand takeover) — consult the PDF report for specifics.

---

## Design & Development Workflow

1. **Concept Generation**  
   Initial sketches and mechanism studies for chest compression actuation.  
2. **CAD Modeling**  
   Developed the structural frame, actuation linkage, and patient interface in CAD.  
3. **Mechanism & Load Analysis**  
   Defined compression stroke, force transmission paths, and mechanical actuators.  
4. **Prototype-Ready Exports**  
   Exported STEP and STL models for simulation, manufacturing, and rapid prototyping.  
5. **Technical Drawing & Documentation**  
   Created PDF drawing documenting dimensions, mounting patterns, tolerances, and assembly instructions.  

---

## How to Use These Models

### Viewing / Editing
- Open STEP files in major CAD tools such as Autodesk Fusion 360, SolidWorks, CATIA, NX, or FreeCAD.  
- Open STL files for 3D printing or mesh-based simulation.

### Integration & Customisation
- Import the chosen STEP file into your CAD assembly.  
- Align the frame or compression module with your patient bed or mounting base.  
- Adapt actuation parameters, patient interface geometry, or mounting points to suit your application.  
- Run simulation or finite element analysis (FEA) for your specific scenarios (load cycles, fatigue, patient interface forces) per the guidelines in the PDF.

---

## Applications

This machine design can be used for:  
- Emergency medical equipment for hospitals or ambulances.  
- Prototype development for automated CPR devices.  
- Educational or research platforms exploring mechanical assist systems in life-safety applications.  
- Outreach projects demonstrating mechanical design, actuation, and biomedical device integration.

---

