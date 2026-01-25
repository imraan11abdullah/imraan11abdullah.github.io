---
layout: post
title: Reinforced Concrete Slab & Beam Design
date: 2024-05-01
description: >
  Individual reinforced concrete slab and beam design project focusing on serviceability-controlled slab thickness selection, gravity load assessment,
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
This individual project involved the structural design of a reinforced concrete
one-way slab system supported by beams, completed in accordance with NZS 3101 (New
Zealand concrete design standard). The emphasis was on serviceability-controlled
thickness selection, load assessment, structural action interpretation, and detailing
of reinforcement.

---

## Structural System Description
The floor slab behaves as a **one-way solid slab** spanning between reinforced
concrete beams. The support conditions are:

- **End spans:** One end continuous, one end pinned  
- **Interior spans:** Both ends continuous  

These conditions influence slab thickness, bending behaviour, and reinforcement
locations.

{% include image-gallery.html images="ONE_WAY_SLAB_FLOOR_PLAN.jpg" height="450" %}
*Floor plan showing one-way slab action and beam support layout*

---

## Slab Thickness Selection (Serviceability)
Slab thickness was based on serviceability limits from **NZS 3101 Section 2.4.3.1**,
which gives span-to-depth ratios for one-way slabs.

For end spans:

- Span (L) = 3.4 m  
- Limiting ratio = L/30  
- Required thickness = 3.4 ÷ 30 = 113.33 mm

For interior spans:

- Span (L) = 3.0 m  
- Limiting ratio = L/35  
- Required thickness = 3.0 ÷ 35 = 85.71 mm

The **end span condition (L/30)** governs the thickness requirement.

{% include image-gallery.html images="NZS3101_THICKNESS_CRITERIA.jpg, BEAM_SECTION.jpg" height="350" %}
*NZS 3101 thickness criteria and beam section detail*

---

## Adopted Slab Thickness
To satisfy serviceability requirements and ensure adequate concrete cover and
reinforcement placement, a slab thickness of **130 mm** was adopted.

Concrete cover and reinforcement allowances:

- Top cover = 45 mm  
- Bottom cover = 45 mm  
- Main reinforcement = 20 mm  
- Thermal reinforcement = 20 mm

Total = 45 + 45 + 20 + 20 = **130 mm**

{% include image-gallery.html images="SLAB_THICKNESS_AND_COVER.jpg" height="350" %}
*Slab thickness arrangement showing main, thermal reinforcement, and cover*

---

## Gravity Load Assessment

Dead load (G) was calculated using the slab thickness and concrete density:

G = 25 × 0.130 = 3.25 kPa

Including finishes and partitions:

G = 3.25 + 0.50 = **3.75 kPa**

This dead load was used to determine slab actions and influence reinforcement demand.

---

## Structural Behaviour Under Load
Under gravity loads, the slab exhibits:

- **Positive bending** at mid-span (governs bottom reinforcement)  
- **Negative bending** over continuous supports (governs top reinforcement)  
- **Shear forces** concentrated near supports

These internal force distributions governed the reinforcement decisions.

{% include image-gallery.html images="BENDING_SHEAR_COLLAGE.jpg" height="450" %}
*Positive bending, negative bending, and shear force positions*

---

## Reinforcement Classification
Reinforcement was grouped by structural role:

- **Main reinforcement:** Resists design bending moments  
- **Thermal reinforcement:** Controls shrinkage and temperature cracking  
- **Top reinforcement:** Resists negative bending over supports  
- **Bottom reinforcement:** Resists positive bending at mid-span  

Concrete cover complied with NZS 3101 for durability and fire resistance.

---

## Standard 90° Hook Detailing
Standard 90° hooks were used at bar terminations to ensure adequate anchorage.
Hook design followed NZS 3101 provisions for minimum bend diameters and
development lengths.

{% include image-gallery.html images="STANDARD_90_DEGREE_HOOK.jpg" height="350" %}
*Standard 90° hook detail used for reinforcement anchorage*

---

## Final Reinforcement Design – Bar Size & Spacing
Reinforcement sizes and spacing were selected based on governing bending moments at
critical locations along the slab.

| Slab Location | Governing Moment (kN/m) | Bar Size & Spacing |
|--------------|-------------------------|-------------------|
| a | −3.25 | D12 @ 260 mm |
| A | +7.09 | D12 @ 260 mm |
| b | −7.80 | D16 @ 260 mm |
| c | −6.07 | D12 @ 260 mm |
| B | +3.79 | D12 @ 260 mm |
| d | −5.52 | D12 @ 260 mm |
| e | −5.52 | D12 @ 260 mm |
| C | +3.79 | D12 @ 260 mm |
| f | −6.07 | D12 @ 260 mm |
| g | −7.80 | D16 @ 260 mm |
| D | +7.09 | D12 @ 260 mm |
| h | −3.25 | D12 @ 260 mm |

{% include image-gallery.html images="FULL_REINFORCEMENT_DETAIL.jpg" height="500" %}
*Complete slab reinforcement layout with bar sizes and spacing*

---

## Engineering Conclusion
A **130 mm reinforced concrete one-way slab** was designed to satisfy both serviceability
and strength requirements in accordance with NZS 3101. Design decisions were based on
conservative thickness selection, rational interpretation of structural behaviour, and
appropriate reinforcement detailing.

This project demonstrates:
- Application of serviceability-controlled thickness limits  
- Rational load assessment and structural action understanding  
- Clear reinforcement classification and detailing  
- Conservative, buildable engineering judgement
