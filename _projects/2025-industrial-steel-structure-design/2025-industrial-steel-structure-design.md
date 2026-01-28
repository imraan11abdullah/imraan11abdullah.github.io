---
layout: post
title: Industrial Steel Structure Design – Industry Project (Part A + Part B)
date: 2025-10-01
description: >
  Comprehensive structural engineering design of an industrial steel building,
  including architectural coordination, gravity, wind and seismic loading,
  SAP2000 analysis, governing ULS assessment, steel member and connection design,
  and foundation design and layout.
skills:
  - Structural steel design (AS 4100)
  - Wind & seismic loading (NZS 1170)
  - SAP2000 modelling & analysis
  - ULS & SLS load combinations
  - Axial, bending & shear interaction
  - Foundation design & Revit coordination
main-image: /3D_BUILDING_VIEW.jpg
---

## Project Introduction
This project involved the **full structural engineering design of an industrial steel
building**, undertaken as a year-long industry project and delivered across
**Part A (concept and interim design)** and **Part B (final detailed engineering design)**.

The scope covered the complete engineering workflow:
- Structural system selection
- Load derivation (gravity, wind, earthquake)
- SAP2000 analysis and verification
- Governing ULS identification
- Steel member and connection design
- Foundation design and layout coordination

---

## Building Description & Function
The development is a **steel-framed industrial facility**, designed to support
industrial operations requiring:
- Large open internal spaces
- Efficient long-span framing
- Robust performance under lateral actions
- Practical and buildable foundations

The structure was designed to ensure clear load paths from roof and floor systems,
through steel members, and into the foundations.

> *(Insert SITE view image here)*  
**Figure 1:** Site view illustrating the context and footprint of the industrial development.

---

## Architectural & Structural Form
The overall building form and layout were developed prior to structural analysis to
define member spans, tributary areas, and load paths.

> *(Insert 3D BUILDING VIEW image here)*  
**Figure 2:** 3D building view showing the overall structural form and industrial scale.

---

## Part A – Concept & Interim Structural Design
Part A established the **structural strategy**, preliminary sizing, and initial analytical
model.

> *(Insert Poster 1 image here)*  
**Figure 3:** Part A poster summarising concept design, load paths, and preliminary analysis.

---

## Structural Analysis Model (SAP2000)
A full **3D SAP2000 model** was developed to analyse the structure under combined
gravity, wind, and earthquake loading.

The model included:
- Steel beams and columns
- Boundary conditions and restraints
- Mass distribution based on tributary areas
- Load cases per NZS 1170

> *(Insert SAP_MODEL_IMAGE_LINK here)*  
**Figure 4:** SAP2000 analytical model used for structural analysis.

---

## Load Assessment (NZS 1170)

### Dead and Live Loads
Dead loads included:
- Structural steel self-weight (auto-generated in SAP2000)
- Permanent building components

Live loads were applied in accordance with **NZS 1170.1** for industrial occupancy.

Load on members was calculated using tributary area methods:

Q = q × A_tributary

---

### Wind and Earthquake Loads
Wind actions were calculated in accordance with **NZS 1170.2**, while seismic actions
were derived per **NZS 1170.5**.

Earthquake base shear was determined using:

V = C(T) × W_t

Vertical distribution:

F_i = V × (W_i × h_i) / Σ(W × h)

Both wind and earthquake loads were applied in orthogonal directions.

---

## Load Combinations & Governing ULS Case
A full set of **ULS and SLS load combinations** was assessed.

ULS combinations included:
- 1.2G + 1.5Q
- G + Q + W
- G + Q + E

It was found that **ULS load combinations governed the design**, producing the
maximum member actions.

> *(Insert LOAD_COMBINATION_TABLE_IMAGE here)*  
**Figure 5:** Load combination table showing governing ULS cases.

---

## Structural Response & Deformed Shape
Structural behaviour under governing ULS loading was assessed to verify stability,
drift, and load distribution.

> *(Insert DEFORMED_SHAPE_IMAGE here)*  
**Figure 6:** SAP2000 deformed shape under governing ULS loading.

---

## SAP2000 Member Actions (ULS)
For the governing ULS case, the following member actions were extracted:

- Axial force (N)
- Major-axis bending moment (M3)
- Shear force (V2)

Only worst-case ULS envelopes were used for design.

> *(Insert AXIAL sap2000 image here)*  
**Figure 7:** Axial force distribution from SAP2000 (ULS).

> *(Insert MOMENT 3-3 image here)*  
**Figure 8:** Major-axis bending moment (M3) envelope under ULS.

> *(Insert Shear 2-2 image here)*  
**Figure 9:** Shear force (V2) envelope under ULS.

---

## Steel Member Design (AS 4100)

### Beam and Column Design
Steel members were designed in accordance with **AS 4100**.

Beam checks:
- M* ≤ φM_b  
- V* ≤ φV_v  

Column interaction check:

(N* / φN_c) + (M* / φM_b) ≤ 1.0

> *(Insert PMM_INTERACTION_IMAGE here)*  
**Figure 10:** PMM interaction check confirming column adequacy under ULS.

---

## Hand Calculations vs SAP2000 Verification
Key member actions and capacities were verified using **hand calculations** to
cross-check SAP2000 results.

> *(Insert hand vs sap calculations image here)*  
**Figure 11:** Comparison between hand calculations and SAP2000 outputs.

---

## Steel Connection Design
Steel connections were designed to safely transfer:
- Axial forces
- Shear forces
- Bending moments

Connections were detailed to ensure **ductile member behaviour governs**.

> *(Insert CONNETCTION steel image here)*  
**Figure 12:** Steel connection detailing and force transfer.

---

## Foundation Design & Load Transfer
Column reactions from SAP2000 were used for foundation design, including:
- Axial load
- Overturning moment
- Shear force

Bearing pressure:

q = N / A

Sliding and overturning checks were also carried out.

> *(Insert FOUNDATION_FORCES and layoutplan image here)*  
**Figure 13:** Foundation reactions and layout plan.

> *(Insert FOUNDATION_FORCES_2 closer look image here)*  
**Figure 14:** Detailed view of foundation forces from SAP2000.

---

## Ground Conditions
Foundation design was informed by the geotechnical investigation.

> *(Insert Geotechnical Investigation image here)*  
**Figure 15:** Summary of subsurface conditions informing foundation design.

---

## Part B – Final Design Resolution
Part B consolidated all analysis into a **final coordinated structural solution**,
including final member sizing, connection checks, and foundation design.

> *(Insert Poster 2 image here)*  
**Figure 16:** Part B poster summarising final structural design and verification.

---

## Engineering Conclusion
This project demonstrates:
- Full structural design workflow from concept to final design
- Governing ULS identification using SAP2000
- Steel member and connection design to AS 4100
- Wind and seismic assessment to NZS 1170
- Integrated foundation design and coordination

It represents the **most technically rigorous and industry-aligned project** in my
portfolio.
