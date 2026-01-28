---
layout: post
title: Industrial Steel Structure Design – Industry Project (Part A + Part B)
date: 2025-10-01
description: >
  Full structural engineering design of an industrial steel building, including
  architectural coordination, gravity, wind and seismic loading, SAP2000 analysis,
  governing ULS assessment, steel member design, and foundation design and layout.
skills:
  - Structural steel design (AS 4100)
  - Wind & seismic loading (NZS 1170)
  - SAP2000 modelling & analysis
  - ULS & SLS load combinations
  - Axial, bending & shear interaction
  - Foundation design & Revit coordination
main-image: /industrial-project-main.jpg
---

## Project Introduction
This project involved the **complete structural engineering design of an industrial steel
building**, undertaken as a year-long industry-focused capstone project.

The objective was to deliver a **code-compliant, buildable structural solution**, progressing
from concept design through to final detailed engineering resolution.

The project was delivered in two stages:
- **Part A:** Concept development and interim structural design
- **Part B:** Final structural analysis, member design, and foundation resolution

---

## Building Description & Function
The development is an **industrial facility** designed to accommodate large open internal
spaces, requiring:
- Long structural spans
- Efficient gravity load transfer
- Robust resistance to wind and earthquake actions
- Practical foundation solutions compatible with site conditions

The structure is primarily a **steel-framed system**, selected for constructability,
structural efficiency, and seismic performance.

---

## Architectural & Structural Layout (Revit)

### Floor Plan Layout
> *(Insert Revit floor plan image here)*  
**Figure 1:** Revit floor plan showing column grid, beam layout, and primary load paths.

### 3D Building Model
> *(Insert Revit 3D model image here)*  
**Figure 2:** 3D Revit model illustrating the overall form and scale of the industrial building.

These models were used to:
- Define tributary areas for load calculations
- Establish member spans and connectivity
- Coordinate column and foundation locations

---

## Part A – Concept & Interim Structural Design
Part A focused on establishing the **structural system and engineering strategy**, including:
- Selection of steel framing system
- Preliminary member sizing
- Initial SAP2000 modelling
- Identification of critical gravity and lateral load cases

> *(Insert Part A poster image here)*  
**Figure 3:** Part A poster summarising the concept design and preliminary structural analysis.

---

## Structural Analysis Model (SAP2000)
A full **3D analytical model** was developed in **SAP2000** to assess structural behaviour
under gravity, wind, and earthquake loading.

The model included:
- Beams and columns represented as frame elements
- Appropriate boundary conditions and restraints
- Rigid diaphragm assumptions at floor levels
- Mass distribution based on tributary areas

> *(Insert SAP2000 model screenshot here)*  
**Figure 4:** SAP2000 3D structural model used for analysis.

---

## Load Assessment (NZS 1170)

### Dead Load (G)
Dead loads included:
- Self-weight of structural steel (automatically generated in SAP2000)
- Floor systems
- Permanent finishes and services

Total dead load was calculated as:

G = G_steel + G_floor + G_services

Dead loads were applied as line and area loads based on tributary widths derived from the
Revit model.

---

### Live Load (Q)
Live loads were applied in accordance with **NZS 1170.1** for industrial occupancy.

Live load on a supporting member:

Q = q × A_tributary

Where:
- q = specified live load (kPa)
- A_tributary = tributary area supported by the member

---

### Wind Load (W)
Wind actions were derived in accordance with **NZS 1170.2**.

Design wind pressure was calculated as:

p = 0.5 × ρ × V_des² × C_fig × C_dyn

Where:
- ρ = air density
- V_des = design wind speed
- C_fig = aerodynamic shape factor
- C_dyn = dynamic response factor

Equivalent lateral wind forces were applied at each floor level in SAP2000.

---

### Earthquake Load (E)
Seismic actions were calculated in accordance with **NZS 1170.5**.

Base shear was determined using:

V = C(T) × W_t

Where:
- C(T) = seismic coefficient based on structural period
- W_t = total seismic weight of the structure

Vertical distribution of seismic forces:

F_i = V × (W_i × h_i) / Σ(W × h)

Seismic loading was applied independently in orthogonal directions.

---

## Load Combinations & Governing Design Case

### Ultimate Limit State (ULS)
The following ULS load combinations were assessed:

- 1.2G + 1.5Q  
- G + Q + W  
- G + Q + E  

All combinations were analysed in SAP2000.

After reviewing all results, **ULS combinations were found to govern the design**, producing
the highest axial forces, bending moments, and shear forces.

> *(Insert ULS load combination table from report here)*  
**Figure 5:** Governing ULS load combinations extracted from SAP2000.

---

## SAP2000 Structural Actions
For the governing ULS cases, the following actions were extracted from SAP2000:

- Axial force (N)
- Major-axis bending moment (M3)
- Shear force (V)

Only **worst-case ULS envelopes** were used for member design.

> *(Insert SAP2000 axial, moment, and shear output images here)*  
**Figure 6:** SAP2000 axial force, bending moment (M3), and shear force envelopes.

---

## Steel Member Design (AS 4100)

### Beam Design
Beams were designed for bending and shear.

Bending check:

M* ≤ φM_b

Shear check:

V* ≤ φV_v

Where:
- M* = design bending moment from SAP2000
- V* = design shear force from SAP2000
- φ = capacity reduction factor

---

### Column Design – Axial and Bending Interaction
Columns were designed for combined axial force and bending using interaction checks:

(N* / φN_c) + (M* / φM_b) ≤ 1.0

Critical columns were assessed under governing ULS load combinations.

---

## Part B – Final Design Resolution
Part B consolidated all analysis into a **fully resolved structural design**, including:
- Final member sizes
- Governing load combinations
- SAP2000 verification
- Compliance with NZS 1170 and AS 4100

> *(Insert Part B poster image here)*  
**Figure 7:** Part B poster summarising the final structural design and verification.

---

## Foundation Design & Load Transfer
Column reactions extracted from SAP2000 included:
- Axial load (N)
- Moment (M)
- Shear (V)

Foundations were designed using:

Bearing pressure:

q = N / A

Overturning:

M_resisting ≥ M_overturning

Sliding:

R_friction ≥ V_horizontal

> *(Insert foundation reaction table from report here)*  
**Figure 8:** Column reactions used for foundation design.

---

## Foundation Layout & Coordination (Revit)
Foundations were modelled in **Revit** to ensure:
- Alignment with column grid
- Constructable footing sizes
- Clear load paths from superstructure to ground

> *(Insert Revit foundation layout image here)*  
**Figure 9:** Revit foundation layout showing coordinated substructure design.

---

## Engineering Conclusion
This project demonstrates **complete structural engineering capability**, including:

- Load derivation using NZS 1170
- Identification of governing ULS conditions
- SAP2000 analysis and envelope extraction
- Steel member design to AS 4100
- Foundation design and Revit coordination

It represents the **most comprehensive and technically rigorous project** in my portfolio
and closely reflects industry-standard structural engineering practice.
