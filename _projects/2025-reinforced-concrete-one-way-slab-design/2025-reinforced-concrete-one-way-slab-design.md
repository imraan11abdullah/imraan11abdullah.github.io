---
layout: post
title: Reinforced Concrete One-Way Slab Design – Residential Building
date: 2025-05-10
description: >
  Structural analysis and reinforced concrete design of a one-way slab system for a
  residential building, including load calculations, bending and shear checks, and
  detailing in accordance with NZS 3101 and NZS 1170.
skills:
  - Reinforced concrete design
  - Structural load calculations
  - Bending moment analysis
  - Shear capacity checks
  - NZS 3101 compliance
  - Engineering judgement
main-image: /rc-slab-main.jpg
---

🔗 **[CLICK HERE TO VIEW FULL STRUCTURAL DESIGN CALCULATIONS (PDF)](PASTE_GOOGLE_DRIVE_LINK){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
This project involved the **individual structural design of a reinforced concrete one-way
slab** for a residential building located in **Ākitio, New Zealand**. The slab was designed
using the **simplified method permitted under NZS 3101**, with full checks carried out for
strength, durability, and serviceability.

**Key Design Inputs:**
- Concrete strength, f'c = 30 MPa  
- Reinforcement grade = 300E  
- Design working life = 50 years  
- Selected slab thickness = 130 mm  

{% include image-gallery.html images="FLOOR_PLAN_IMAGE_URL, TRIBUTARY_WIDTH_IMAGE_URL" height="500" %}

---

## One-Way Slab Configuration
Initial span assessment showed that a **three-span slab configuration** did not comply
with the simplified method requirements of NZS 3101, where adjacent spans must satisfy:

Li / Lj ≤ 1.2

To comply with the standard and allow use of the simplified design method, the slab was
reconfigured to a **four-span layout**, which satisfied all span ratio requirements.

{% include image-gallery.html images="SPAN_CONFIGURATION_IMAGE_URL" height="450" %}

---

## Load Calculations

### Dead Load (G)
Self-weight of slab:  
25 kN/m³ × 0.13 m = 3.25 kPa  

Finishes and superimposed dead load:  
= 0.50 kPa  

Total dead load:  
G = 3.25 + 0.50  
G = **3.75 kPa**

### Live Load (Q)
Residential live load (NZS 1170.1):  
Q = **1.5 kPa**

### Ultimate Limit State Load
ULS combination:  
1.2G + 1.5Q  

= 1.2(3.75) + 1.5(1.5)  
= 4.50 + 2.25  
= **6.75 kPa**

---

## Bending Moment Calculations
Bending moments were calculated using the simplified coefficients from NZS 3101.

Effective span length:  
L = 3.4 m  

### Positive Bending Moment
M+ = WL² / 11  

= 6.75 × 3.4² / 11  
= 6.75 × 11.56 / 11  
= **7.09 kN·m/m**

### Negative Bending Moment
M− = WL² / 10  

= 6.75 × 3.4² / 10  
= **7.80 kN·m/m**

{% include image-gallery.html images="BENDING_MOMENT_IMAGE_URL" height="500" %}

---

## Reinforcement Design

### Effective Depth
Overall slab thickness = 130 mm  
Concrete cover = 45 mm  
Bar diameter = 20 mm  

Effective depth:  
d = 130 − 45 − (20 / 2)  
d = **75 mm**

### Reinforcement Selection
Reinforcement was selected to resist calculated bending moments while satisfying minimum
reinforcement requirements of NZS 3101.

| Location | Design Moment | Reinforcement |
|--------|---------------|---------------|
| End spans (+/−) | 7.09 kN·m/m | D12 @ 260 mm |
| Interior supports | 7.80 kN·m/m | D16 @ 260 mm |
| Shrinkage & temperature | — | D10 @ 390 mm |

{% include image-gallery.html images="REINFORCEMENT_DETAIL_IMAGE_URL" height="500" %}

---

## Shear Capacity Check
Design shear force:  
V* = **13.19 kN**

Concrete shear capacity:  
ϕVc = **46.86 kN**

Check:  
V* < ϕVc  
13.19 < 46.86 ✓  

Therefore, **no shear reinforcement is required**.

---

## Durability Considerations
The site is classified as **B2 exposure** due to proximity to the coastline
(approximately 484 m).

Minimum concrete cover required:  
= **45 mm**

All durability requirements for a 50-year design life are satisfied in accordance with
NZS 3101.

---

## Engineering Design Conclusion
A **130 mm reinforced concrete one-way slab** was successfully designed using the NZS 3101
simplified method.

**Design Summary:**
- All ULS bending and shear requirements satisfied  
- Span configuration compliant with NZS 3101  
- Reinforcement meets strength and durability criteria  
- No shear reinforcement required  
- Practical and buildable detailing achieved  

This project demonstrates sound application of reinforced concrete theory, code
interpretation, and engineering judgement in structural slab design.
