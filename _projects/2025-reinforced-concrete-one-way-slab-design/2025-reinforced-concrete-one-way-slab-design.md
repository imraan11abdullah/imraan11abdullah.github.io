---
layout: post
title: Reinforced Concrete One-Way Slab Design
date: 2025-06-06
description: >
  Structural design of a reinforced concrete one-way slab in accordance with NZS 3101,
  including slab action classification, serviceability-controlled thickness selection,
  gravity load assessment, reinforcement design, and detailing.
skills:
  - Reinforced concrete design
  - NZS 3101 application
  - Serviceability design
  - Structural load analysis
  - Reinforcement detailing
main-image: /final-slab-reinforcement.png
---

## Structural Layout and One-Way Action
The slab system was classified as a **one-way slab** based on span geometry and support
conditions. Load transfer occurs predominantly in a single direction, with the slab
spanning between parallel supporting beams.

{% include image-gallery.html images="
https://i.ibb.co/0VfxyN2K/Structural-Layout-and-One-Way-Action.png
" height="500" %}
*Structural layout and one-way slab action*

---

## Slab Thickness Selection (Serviceability)
Slab thickness was governed by **serviceability requirements**, primarily long-term
deflection control, in accordance with **NZS 3101:2006 Section 2.4.3.1**.

The span-to-depth ratios for solid one-way slabs were adopted:

- End spans (one end continuous, one end pinned): L / 30  
- Interior spans (both ends continuous): L / 35  

The most critical span condition governed the design thickness.

---

## Adopted Slab Thickness
A slab thickness of **130 mm** was adopted.

This thickness:
- Satisfies deflection control requirements  
- Accommodates reinforcement cover and bar diameters  
- Provides conservative structural performance  
- Allows practical construction tolerances  

{% include image-gallery.html images="
https://i.ibb.co/xqG9xRSs/Adopted-Slab-Thickness.png
" height="400" %}
*Adopted slab thickness and reinforcement cover requirements*

---

## Gravity Load Assessment
Dead load was calculated based on slab self-weight and permanent finishes.

Self-weight of reinforced concrete slab:

G = γ × t  
G = 25 kN/m³ × 0.130 m  
G = 3.25 kPa  

Including finishes and partitions:

G = 3.25 + 0.50  
G = **3.75 kPa**

This gravity load formed the basis of flexural and shear assessment.

---

## Structural Behaviour Under Load
The slab was analysed using classical one-way bending theory under uniformly distributed
gravity loading.

Key internal actions considered:
- **Positive bending moments** at mid-span  
- **Negative bending moments** over continuous supports  
- **Shear forces** near supports  

Standard elastic beam equations were used to determine critical design actions in
accordance with NZS 3101.

{% include image-gallery.html images="
https://i.ibb.co/r2sLcNFV/Positive-bending-negative-bending-and-shear-force-regions.jpg
" height="600" %}
*Positive bending, negative bending, and shear force regions*

---

## Reinforcement Classification
Reinforcement was classified based on its structural function within the slab system:

- **Main reinforcement:** resists flexural tensile stresses  
- **Thermal reinforcement:** controls shrinkage and temperature effects  
- **Top reinforcement:** resists negative bending over supports  
- **Bottom reinforcement:** resists positive bending at mid-span  

{% include image-gallery.html images="
https://i.ibb.co/BH9GDpvt/Reinforcement-Classification.png
" height="400" %}
*Reinforcement classification and structural role*

---

## Reinforcement Detailing and Anchorage
Reinforcement anchorage was achieved using **standard 90° hooks** in accordance with
NZS 3101 detailing provisions.

This detailing:
- Ensures sufficient development length  
- Prevents bar pull-out  
- Improves structural reliability and constructability  

{% include image-gallery.html images="
https://i.ibb.co/wNFYZrpQ/Standard-90-Hook-Detailing.png
" height="400" %}
*Standard 90° hook detailing*

---

## Final Reinforcement Design – Bar Size & Spacing
Final reinforcement sizes and spacing were selected based on governing bending moments
at critical slab locations.

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

---

## Final Slab Reinforcement Layout
The final reinforcement layout integrates all design decisions, including slab thickness,
bar sizes, spacing, cover requirements, and anchorage detailing.

{% include image-gallery.html images="
https://i.ibb.co/RkRdr5Cq/final-slab-reinforcement.png
" height="550" %}
*Final slab reinforcement detailing*

---

## Engineering Conclusion
The reinforced concrete one-way slab was designed in accordance with **NZS 3101**,
satisfying both **strength** and **serviceability** requirements.

Key outcomes:
- Serviceability-controlled slab thickness  
- Clear identification of load paths and bending behaviour  
- Reinforcement sized and detailed for governing moments  
- Code-compliant anchorage and spacing  

This project demonstrates sound application of reinforced concrete theory, structural
analysis, and practical detailing suitable for real-world construction.
