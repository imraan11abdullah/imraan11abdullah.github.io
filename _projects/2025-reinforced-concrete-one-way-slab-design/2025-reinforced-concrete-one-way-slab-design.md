---
layout: post
title: Reinforced Concrete Slab & Beam Design
date: 2024-05-01
description: >
  Individual reinforced concrete slab and beam design project focusing on
  serviceability-controlled thickness selection, gravity load assessment,
  structural behaviour, and reinforcement detailing in accordance with NZS 3101.
skills:
  - Reinforced concrete design
  - Serviceability assessment
  - Load calculations
  - Structural behaviour interpretation
  - Reinforcement detailing
  - Engineering judgement
main-image: /slab-overview.jpg
---

🔗 **[CLICK HERE TO VIEW FULL STRUCTURAL DESIGN REPORT (PDF)](PASTE_GOOGLE_DRIVE_LINK_HERE){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
This individual project involved the design of a **reinforced concrete one-way slab
system supported by beams**, carried out in accordance with **NZS 3101:2006**.
The design focused on controlling **serviceability behaviour**, assessing gravity
loading, and detailing reinforcement based on the resulting structural actions.

Rather than relying solely on software output, the project emphasised
**first-principles understanding**, conservative assumptions, and clear justification
of design decisions.

---

## Structural System Description
The slab system behaves as a **one-way solid slab** spanning between reinforced
concrete beams. Different support conditions govern the structural behaviour:

- **End bays:** One end continuous, one end pinned  
- **Interior bays:** Both ends continuous  

These conditions directly influence slab thickness requirements, bending behaviour,
and reinforcement placement.

{% include image-gallery.html images="SLAB_LAYOUT.jpg, BEAM_LAYOUT.jpg" height="450" %}
*Slab layout and beam support configuration*

---

## Slab Thickness Selection  
**NZS 3101:2006 – Serviceability-Based Design**

Slab thickness was governed by **deflection control requirements** using the
span-to-depth ratios provided in  
**NZS 3101 Section 2.4.3.1 (Slabs and beams for buildings)**.

Design assumptions:
- One-way slab action  
- Steel yield strength: **f<sub>y</sub> = 300 MPa**

### Governing Span-to-Depth Criteria

| Span Location | Limiting Ratio | Span (L) | Required Thickness |
|--------------|---------------|----------|--------------------|
| End bays | L / 30 | 3.4 m | 113.33 mm |
| Interior bays | L / 35 | 3.0 m | 85.71 mm |

The **end bay condition (L/30)** governed slab thickness and therefore controlled the
overall design.

{% include image-gallery.html images="NZS3101_THICKNESS_CRITERIA.jpg" height="350" %}
*NZS 3101 serviceability criteria for slab thickness*

---

### Adopted Slab Thickness
A slab thickness of:

\[
\boxed{130 \text{ mm}}
\]

was adopted to:
- Exceed the minimum serviceability requirement  
- Accommodate reinforcement and concrete cover  
- Allow for construction tolerances  
- Maintain conservative engineering practice  

Cover and reinforcement allowance:
- Top cover = 45 mm  
- Bottom cover = 45 mm  
- Primary reinforcement = 20 mm  
- Secondary reinforcement = 20 mm  

This ensured the slab comfortably exceeded the minimum required thickness while
remaining practical to construct.

{% include image-gallery.html images="SLAB_THICKNESS_DETAIL.jpg" height="350" %}
*Slab thickness and reinforcement cover arrangement*

---

## Gravity Load Assessment
Dead load was calculated based on the adopted slab thickness and material properties.

Self-weight of concrete slab:
\[
G = 25 \, \text{kN/m}^3 \times 0.130 \, \text{m} = 3.25 \, \text{kPa}
\]

Including floor finishes and allowance for partitions:
\[
G = 3.25 + 0.50 = \boxed{3.75 \, \text{kPa}}
\]

These actions formed the basis for assessing slab behaviour and reinforcement demand.

---

## Structural Behaviour
Under gravity loading, the slab experiences:
- **Positive bending** at mid-span regions, governing bottom reinforcement  
- **Negative bending** over continuous supports, governing top reinforcement  
- **Peak shear forces** near supports, diminishing toward mid-span  

The distribution of these internal forces was used to identify **critical design
locations**, rather than designing the slab uniformly along its length.

{% include image-gallery.html images="BENDING_AND_SHEAR_OVERVIEW.jpg" height="450" %}
*Structural behaviour under gravity loading*

---

## Reinforcement Design & Detailing
Reinforcement sizes and spacing were selected based on the governing bending moments
at each critical location along the slab.

| Point on Slab | Governing Moment (kN/m) | Bar Size & Spacing |
|--------------|-------------------------|-------------------|
| a | -3.25 | D12 @ 260 mm |
| A | +7.09 | D12 @ 260 mm |
| b | -7.80 | D16 @ 260 mm |
| c | -6.07 | D12 @ 260 mm |
| B | +3.79 | D12 @ 260 mm |
| d | -5.52 | D12 @ 260 mm |
| e | -5.52 | D12 @ 260 mm |
| C | +3.79 | D12 @ 260 mm |
| f | -6.07 | D12 @ 260 mm |
| g | -7.80 | D16 @ 260 mm |
| D | +7.09 | D12 @ 260 mm |
| h | -3.25 | D12 @ 260 mm |

{% include image-gallery.html images="REINFORCEMENT_LAYOUT_FULL.jpg, BAR_SPACING_DETAIL.jpg" height="500" %}
*Final reinforcement layout showing bar sizes and spacing*

---

## Engineering Conclusion
A **130 mm thick one-way reinforced concrete slab** was designed to satisfy
serviceability and strength requirements under gravity loading.

This project demonstrates:
- Appropriate application of **NZS 3101 serviceability criteria**
- Rational slab thickness selection based on governing span conditions
- Clear understanding of slab structural behaviour
- Reinforcement detailing aligned with calculated demands
- Conservative and buildable engineering judgement

