---
layout: post
title: Industrial Steel Structure Design – Industry Project 
date: 2025-10-01
description: >
  End-to-end structural engineering design of an industrial steel building, including SAP2000
  modelling, gravity and seismic load assessment, steel member and connection design, and
  foundation interface checks in accordance with NZS 1170.5 and AS 4100.
skills:
  - Structural steel design (AS 4100)
  - Seismic design (NZS 1170.5)
  - SAP2000 modelling & analysis
  - Gravity & lateral load assessment
  - PMM interaction checks
  - Steel connection design
  - Foundation load transfer
main-image: /industrial-steel-main.jpg
---

## Project Overview
This industry-based capstone project involved the **complete structural engineering design
of an industrial steel building**, delivered across **Part A (concept + interim design)** and
**Part B (final detailed engineering resolution)**.

The project required:
- Structural system selection
- Gravity and seismic load modelling
- Detailed steel member design
- Connection force verification
- Foundation interface assessment

All analysis was performed using **SAP2000**, with seismic actions derived from
**NZS 1170.5** and steel members designed in accordance with **AS 4100**.

---

## Structural System & Engineering Strategy
A **combined structural system** was adopted to balance stiffness, ductility, and constructability:

- **Moment-resisting steel frames**  
  → Primary ductile energy dissipation  
- **Steel braced frames**  
  → Drift control and seismic force reduction  

This approach allowed:
- Reduced seismic demands on individual members
- Efficient inter-storey drift control
- Redundancy in lateral load paths

---

## Poster 1 – Concept Design & Structural Strategy
Poster 1 presents the **initial engineering decisions**, including:

- Column grid and framing layout
- Identification of gravity and lateral load paths
- Preliminary member sizing
- Seismic design intent

{% include image-gallery.html images="POSTER_1_IMAGE_LINK" height="500" %}

---

## SAP2000 Structural Modelling
A full **3D SAP2000 model** was developed to represent:

- Beams, columns, and bracing elements
- Support conditions and fixities
- Rigid diaphragm behaviour at floor levels
- Mass distribution derived from tributary areas

Modal analysis confirmed:
- Acceptable fundamental period
- Adequate mass participation in primary modes

{% include image-gallery.html images="SAP_MODEL_IMAGE_LINK" height="500" %}

---

## Gravity Load Assessment (NZS 1170.1)

### Dead Load (G)
Dead loads included:
- Steel self-weight
- Floor systems
- Permanent finishes and services

Symbolically:

G = Σ (unit weight × thickness)

Typical floor dead load:
- Structural + finishes = **G = 4.5 kPa**

### Live Load (Q)
Industrial live loads applied per NZS 1170.1:
- Typical floor live load = **Q = 3.0 kPa**

---

## Load Combinations
Load combinations were generated within SAP2000.

### Ultimate Limit State (ULS)
- 1.2G + 1.5Q  
- G + Q + E  

### Serviceability Limit State (SLS)
- G + Q  
- G + 0.7E  

Where:
- E = seismic action (NZS 1170.5)

{% include image-gallery.html images="LOAD_COMBINATION_TABLE_IMAGE" height="450" %}

---

## Seismic Design Basis (NZS 1170.5)
Seismic actions were derived using the **equivalent static method** and verified using
modal response spectrum analysis.

Base shear calculated as:

V = C(T) × Wt

Where:
- C(T) = seismic coefficient
- Wt = total seismic weight

Key parameters:
- Seismic hazard factor (Z)
- Ductility factor (μ)
- Structural performance factor (Sp)

{% include image-gallery.html images="SEISMIC_LOAD_TABLE_IMAGE" height="450" %}

---

## Lateral Load Distribution
Seismic forces were distributed vertically based on:
- Storey mass
- Storey height

Inter-storey drift was checked against serviceability limits and satisfied code requirements.

{% include image-gallery.html images="DEFORMED_SHAPE_IMAGE" height="500" %}

---

## Steel Member Design (AS 4100)

### Beam Design
Beams were designed for:
- Bending
- Shear
- Deflection (SLS)

Bending capacity check:

M* ≤ φMb

Shear capacity check:

V* ≤ φVv

---

### Column Design & PMM Interaction
Columns were assessed for combined axial force and bending using PMM interaction:

(N*/φNc) + (Mx*/φMbx) + (My*/φMby) ≤ 1.0

SAP2000 PMM envelopes confirmed all columns remained within interaction limits.

{% include image-gallery.html images="PMM_INTERACTION_IMAGE" height="450" %}

---

## Steel Connection Design
Connection forces extracted from SAP2000 included:
- End reactions
- Axial forces in braces
- Shear forces at beam-column joints

Connections were checked for:
- Bolt shear capacity
- Bolt bearing
- Plate bending
- Weld strength

Design philosophy ensured **ductile member behaviour governs**, not brittle connection failure.

{% include image-gallery.html images="CONNECTION_DETAIL_IMAGE" height="450" %}

---

## Poster 2 – Final Design Resolution
Poster 2 summarises the **final engineering solution**, including:

- Final member sizes
- Seismic demand vs capacity
- SAP2000 verification results
- Design compliance summary

{% include image-gallery.html images="POSTER_2_IMAGE_LINK" height="500" %}

---

## Foundation Interface Engineering
Although detailed foundation design was treated separately, structural actions transferred to
foundations were extracted from SAP2000:

- Axial column loads
- Base shears
- Overturning moments

These informed:
- Pad footing sizing
- Bearing pressure checks
- Sliding and overturning stability

{% include image-gallery.html images="FOUNDATION_REACTION_TABLE_IMAGE" height="450" %}

---

## Engineering Outcomes
This project demonstrates:

- Professional-level use of **SAP2000**
- Code-compliant **seismic steel design**
- Integrated gravity and lateral load systems
- Steel member and connection verification
- Clear understanding of load transfer to foundations

This represents the **highest level of applied structural engineering** in my academic
portfolio and closely reflects real-world industry workflows.

