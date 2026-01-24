---
layout: post
title: Reinforced Concrete Slab & Beam Design – Structural Design Assignment
date: 2024-05-01
description: >
  Individual reinforced concrete slab and beam design project involving serviceability
  checks, dead and live load calculations, positive and negative bending moment analysis,
  shear force assessment, and reinforcement sizing in accordance with NZS 3101.
skills:
  - Reinforced concrete design
  - Serviceability design
  - Load calculations
  - Bending moment analysis
  - Shear force analysis
  - Reinforcement detailing
main-image: /slab-overview.jpg
---

🔗 **[CLICK HERE TO VIEW FULL STRUCTURAL DESIGN REPORT (PDF)](PASTE_GOOGLE_DRIVE_LINK_HERE){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
This individual project involved the **structural design of a reinforced concrete slab
system**, including associated beams, in accordance with **NZS 3101:2006**. The design
process focused on **serviceability requirements**, structural action under gravity loads,
and reinforcement detailing based on calculated bending moments and shear forces.

The project emphasised correct engineering judgement, conservative assumptions, and
clear justification of slab thickness and reinforcement layout.

---

## Structural Layout
The slab system consists of **one-way solid slabs** supported by beams with varying
support conditions:

- End bays: **One end continuous, one end pinned**
- Interior bays: **Both ends continuous (fixed)**

{% include image-gallery.html images="SLAB_LAYOUT.jpg, BEAM_LAYOUT.jpg" height="450" %}
*Overall slab and beam layout*

---

## 3.0 Beam & Slab Thickness Design  
**NZS 3101:2006 – Section 2.4 (Serviceability Criteria)**

Slab thickness was determined using the **span-to-depth ratios** specified in  
**Figure 10 – NZS 3101 Section 2.4.3.1 (Slabs and beams for buildings)**.

Assumptions:
- Steel yield strength: **f<sub>y</sub> = 300 MPa**
- One-way solid slab behaviour

### Governing Thickness Criteria

| Span Condition | Limiting Ratio | Span (L) | Required Thickness |
|---------------|---------------|----------|--------------------|
| End bays | L / 30 | 3.4 m | 113.33 mm |
| Interior bays | L / 35 | 3.0 m | 85.71 mm |

\[
t = \frac{L}{30} = \frac{3400}{30} = 113.33 \, \text{mm}
\]

\[
t = \frac{L}{35} = \frac{3000}{35} = 85.71 \, \text{mm}
\]

{% include image-gallery.html images="NZS3101_THICKNESS_CRITERIA.jpg, BEAM_SECTION.jpg" height="400" %}
*NZS 3101 thickness criteria and beam section reference*

---

### Adopted Slab Thickness
To remain **conservative** and allow for construction tolerances, the slab thickness
was increased to:

\[
\boxed{t = 130 \, \text{mm}}
\]

This accommodates:
- 45 mm top cover  
- 45 mm bottom cover  
- 20 mm primary reinforcement  
- 20 mm secondary reinforcement  

\[
45 + 45 + 20 + 20 = 130 \, \text{mm}
\]

{% include image-gallery.html images="SLAB_THICKNESS_DETAIL.jpg" height="350" %}
*Slab thickness and reinforcement cover requirements*

---

## 4.1 Dead Load Calculation

Self-weight of concrete slab:

\[
G = \gamma_c \times t
\]

\[
G = 25 \, \text{kN/m}^3 \times 0.130 \, \text{m}
\]

\[
G = 3.25 \, \text{kPa}
\]

Including floor finishes and partitions:

\[
G = 3.25 + 0.50 = \boxed{3.75 \, \text{kPa}}
\]

---

## Structural Analysis Results

The slab was analysed to determine **positive and negative bending moments** and
corresponding **shear forces** along the slab length.

{% include image-gallery.html images="BENDING_MOMENT_DIAGRAM_POS_NEG.jpg, SHEAR_FORCE_DIAGRAM.jpg" height="450" %}
*Positive & negative bending moments and shear force distribution*

---

## Bending Moment Summary
The table below summarises the governing bending moments obtained from analysis:

| Point | Bending Moment (kN/m) | Moment Type |
|------|----------------------|-------------|
| a | -3.25 | Negative |
| A | +7.09 | Positive |
| b | -7.80 | Negative |
| c | -6.07 | Negative |
| B | +3.79 | Positive |
| d | -5.52 | Negative |
| e | -5.52 | Negative |
| C | +3.79 | Positive |
| f | -6.07 | Negative |
| g | -7.80 | Negative |
| D | +7.09 | Positive |
| h | -3.25 | Negative |

---

## 10.8 Final Reinforcement Design – Bar Size & Spacing

Based on calculated bending moments, reinforcement was sized and detailed as follows:

| Point on Slab | Bending Moment (kN/m) | Bar Size & Spacing |
|--------------|----------------------|-------------------|
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
*Final reinforcement layout, bar sizes, and spacing*

---

## Engineering Conclusion
The final slab and beam design satisfies **serviceability and strength requirements**
under NZS 3101. A conservative slab thickness was adopted to ensure deflection control,
adequate cover, and constructability.

This project demonstrates:
- Correct application of **NZS 3101 serviceability criteria**
- Clear justification of slab thickness selection
- Accurate dead load assessment
- Interpretation of positive and negative bending behaviour
- Reinforcement detailing based on calculated demands

