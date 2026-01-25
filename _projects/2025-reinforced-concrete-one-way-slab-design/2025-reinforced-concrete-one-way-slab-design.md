---
layout: post
title: Reinforced Concrete One-Way Slab Design
date: 2025-06-06
description: >
  Structural design of a reinforced concrete one-way slab in accordance with NZS 3101,
  including slab thickness selection, gravity load assessment, reinforcement detailing,
  and constructability considerations.
skills:
  - Reinforced concrete design
  - NZS 3101 application
  - Serviceability design
  - Flexural behaviour analysis
  - Reinforcement detailing
main-image: /slab-main.jpg
---

## Structural Layout and One-Way Action
The slab system was classified as a **one-way slab** based on span geometry and
support conditions, where load transfer occurs predominantly in a single direction.

{% include image-gallery.html images="
https://i.ibb.co/YB71Gb3Y/Screenshot-2026-01-24-210348.png
" height="500" %}

---

## Slab Thickness Selection (Serviceability)
Slab thickness was governed by **serviceability requirements**, specifically long-term
deflection control under sustained gravity loading, in accordance with
NZS 3101 Section 2.4.3.1.

The **span-to-depth method** was adopted:

- End spans (one end continuous, one end pinned): L / 30  
- Interior spans (both ends continuous): L / 35  

The most critical span condition governs the final slab thickness.

---

## Adopted Slab Thickness
A slab thickness of **130 mm** was adopted.

This thickness:
- Satisfies deflection limits
- Provides adequate flexural stiffness (EI)
- Accommodates reinforcement cover and bar diameters
- Allows conservative and practical construction

{% include image-gallery.html images="
https://i.ibb.co/GvXWStsB/Screenshot-2026-01-24-210117.png
" height="450" %}
*Slab thickness, reinforcement layers, and concrete cover*

---

## Gravity Load Assessment
Dead load was calculated using the self-weight relationship for reinforced concrete.

Self-weight equation:  
G = γ × t  

Where:
- γ = 25 kN/m³ (reinforced concrete)
- t = 0.130 m

Self-weight of slab:  
G = 25 × 0.130 = 3.25 kPa  

Including finishes and partitions:  
G = 3.25 + 0.50 = **3.75 kPa**

This gravity load was used for flexural and shear demand assessment.

---

## Structural Behaviour Under Load
The slab was analysed assuming one-way bending under uniformly distributed gravity load.

Classical beam theory was applied to identify critical internal actions:

- Positive bending moment at mid-span  
  M = wL² / 8  

- Negative bending moment over continuous supports  
  M = wL² / 12  

- Maximum shear near supports  
  V = wL / 2  

{% include image-gallery.html images="
https://i.ibb.co/n8KvFm83/My-Simplecollage-com.jpg
" height="500" %}
*Positive bending, negative bending, and shear force regions*

---

## Reinforcement Classification
Reinforcement was detailed according to its structural function:

- **Main reinforcement:** resists flexural tensile stresses  
- **Thermal reinforcement:** controls shrinkage and temperature cracking  
- **Top reinforcement:** resists negative bending over supports  
- **Bottom reinforcement:** resists positive bending at mid-span  

{% include image-gallery.html images="
https://i.ibb.co/hRbVR3r9/Screenshot-2026-01-24-210050.png
" height="450" %}
*Main and thermal reinforcement configuration*

---

## Standard 90° Hook Detailing
Reinforcement anchorage was achieved using **standard 90° hooks** in accordance with
NZS 3101 detailing requirements.

Hook design ensures:
- Adequate development length
- Effective bond between steel and concrete
- Prevention of anchorage failure

{% include image-gallery.html images="
https://i.ibb.co/ZpwzrY5m/Screenshot-2026-01-24-210320.png
" height="400" %}
*Standard 90° hook detailing*

---

## Final Reinforcement Design – Bar Size & Spacing
Reinforcement was finalised based on calculated bending moment demand at critical
locations along the slab.

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

{% include image-gallery.html images="
https://i.ibb.co/YB71Gb3Y/Screenshot-2026-01-24-210348.png
" height="550" %}
*Final slab reinforcement layout*

---

## Engineering Conclusion
The reinforced concrete one-way slab was successfully designed in accordance with
NZS 3101, satisfying both **strength** and **serviceability** requirements.

Key outcomes:
- Slab thickness governed by deflection control and constructability
- Gravity loads assessed using self-weight principles
- Structural behaviour identified using classical beam theory
- Reinforcement detailed based on tensile demand and crack control
- Anchorage and detailing comply with NZS 3101

This project demonstrates strong understanding of reinforced concrete behaviour,
load paths, and practical engineering judgement suitable for real-world application.
