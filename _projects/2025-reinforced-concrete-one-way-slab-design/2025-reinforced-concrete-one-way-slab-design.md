---
layout: post
title: Reinforced Concrete Slab & Beam Design
date: 2024-05-01
description: >
  Individual reinforced concrete slab and beam design project focusing on
  serviceability-controlled slab thickness selection, gravity load assessment,
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
This individual project involved the structural design of a **reinforced concrete
one-way slab system supported by beams**, undertaken in accordance with
**NZS 3101:2006**. The design focused on **serviceability behaviour**, gravity loading,
and reinforcement detailing, with emphasis on conservative and buildable engineering
decisions.

---

## Structural System Description
The floor system consists of **one-way solid slabs** spanning between reinforced
concrete beams. The support conditions vary across the floor plate:

- **End spans:** One end continuous, one end pinned  
- **Interior spans:** Both ends continuous  

These conditions govern slab thickness requirements, bending behaviour, and
reinforcement placement.

{% include image-gallery.html images="ONE_WAY_SLAB_FLOOR_PLAN.jpg" height="450" %}
*Floor plan showing one-way slab action and beam support layout*

---

## Slab Thickness Selection (Serviceability)
Slab thickness was determined using the **span-to-depth limits** specified in  
**NZS 3101:2006 Section 2.4.3.1**, which controls deflection under service loads.

Design assumptions:
- One-way slab behaviour  
- Reinforcing steel yield strength: **f<sub>y</sub> = 300 MPa**

| Span Location | Limiting Ratio | Span (L) | Required Thickness |
|--------------|---------------|----------|--------------------|
| End spans | L / 30 | 3.4 m | 113.33 mm |
| Interior spans | L / 35 | 3.0 m | 85.71 mm |

The **end span condition (L/30)** governed the design.

---

### Adopted Slab Thickness
A slab thickness of:

$$
\boxed{130 \text{ mm}}
$$

was adopted to:
- Exceed minimum serviceability requirements  
- Allow for reinforcement placement and concrete cover  
- Provide construction tolerance  
- Maintain conservative engineering practice  

Reinforcement and cover allowance:
- Top cover = 45 mm  
- Bottom cover = 45 mm  
- Main reinforcement = 20 mm  
- Thermal reinforcement = 20 mm  

$$
45 + 45 + 20 + 20 = 130 \text{ mm}
$$

{% include image-gallery.html images="SLAB_THICKNESS_AND_COVER.jpg" height="350" %}
*Concrete cover, main reinforcement, and thermal reinforcement arrangement*

---

## Gravity Load Assessment
Dead load was calculated based on the adopted slab thickness and material properties.

Self-weight of concrete slab:

$$
G = 25 \, \text{kN/m}^3 \times 0.130 \, \text{m} = 3.25 \, \text{kPa}
$$

Including floor finishes and allowance for partitions:

$$
G = 3.25 + 0.50 = \boxed{3.75 \, \text{kPa}}
$$

This dead load was used in determining slab actions and reinforcement demand.

---

## Structural Behaviour
Under gravity loading, the slab experiences:
- **Positive bending** at mid-span regions  
- **Negative bending** over continuous supports  
- **Shear forces** concentrated near supports  

Critical reinforcement locations were identified based on these structural actions.

{% include image-gallery.html images="BENDING_SHEAR_COLLAGE.jpg" height="450" %}
*Positive bending, negative bending, and shear force positions along the slab*

---

## Reinforcement Classification
Reinforcement was classified based on its structural role:

- **Main reinforcement:** Resists bending moments  
- **Thermal reinforcement:** Controls shrinkage and temperature cracking  
- **Top reinforcement:** Resists negative bending over supports  
- **Bottom reinforcement:** Resists positive bending at mid-span  

Concrete cover was provided in accordance with durability and fire resistance
requirements of NZS 3101.

---

## Anchorage & Standard Hook Design
Reinforcement anchorage was achieved using **standard 90° hooks**, as permitted by
NZS 3101, to ensure adequate bond and force transfer between steel and concrete.

The hook detail satisfies:
- Minimum bend diameter requirements  
- Development length provisions  
- Anchorage capacity under tensile force  

{% include image-gallery.html images="STANDARD_90_DEGREE_HOOK.jpg" height="350" %}
*Standard 90° hook geometry and anchorage detail*

---

## Final Reinforcement Design – Bar Size & Spacing
Reinforcement sizes and spacing were selected based on governing bending moments at
critical slab locations.

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

{% include image-gallery.html images="FULL_REINFORCEMENT_DETAIL.jpg" height="500" %}
*Complete slab reinforcement layout and detailing*

---

## Engineering Conclusion
A **130 mm thick reinforced concrete one-way slab** was designed to satisfy
serviceability and strength requirements in accordance with **NZS 3101**.

This project demonstrates:
- Rational slab thickness selection based on serviceability limits  
- Clear understanding of slab structural behaviour  
- Appropriate classification and detailing of reinforcement  
- Conservative, buildable engineering judgement aligned with practice
