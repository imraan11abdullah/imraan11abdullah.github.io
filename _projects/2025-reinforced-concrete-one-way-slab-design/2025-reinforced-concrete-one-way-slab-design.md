---
layout: post
title: Reinforced Concrete One-Way Slab Design – Residential Building
date: 2025-05-10
description: >
  Structural analysis and reinforced concrete design of a one-way slab system for a
  residential building, including load assessment, bending and shear checks, serviceability
  considerations, and detailing in accordance with NZS 3101 and NZS 1170.
skills:
  - Reinforced concrete design
  - Structural load analysis
  - Bending and shear calculations
  - Serviceability assessment
  - NZS 3101 compliance
  - Engineering judgement
main-image: /rc-slab-main.jpg
---

🔗 **[CLICK HERE TO VIEW FULL STRUCTURAL DESIGN CALCULATIONS (PDF)](PASTE_GOOGLE_DRIVE_LINK){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
This project involved the **individual structural design of a reinforced concrete one-way
slab system** for a residential building located in **Ākitio, New Zealand**. The slab was
designed using the **simplified method permitted under NZS 3101**, with checks carried out
for strength, durability, and serviceability.

The project focused on demonstrating correct **load assessment, span configuration,
bending moment calculation, and reinforcement detailing** in accordance with New Zealand
standards.

**Key Design Decisions:**
- **Structural System:** One-way reinforced concrete slab
- **Concrete Strength:** 30 MPa
- **Reinforcement Grade:** 300E
- **Design Working Life:** 50 years
- **Selected Slab Thickness:** 130 mm

{% include image-gallery.html images="FLOOR_PLAN_IMAGE_URL, TRIBUTARY_WIDTH_IMAGE_URL" height="500" %}
*Floor layout and slab load distribution*

---

## One-Way Slab Configuration & Span Assessment
Initial assessment of slab spans indicated that a **three-span configuration did not satisfy**
the simplified method requirements under **NZS 3101 Clause 6.7.2.1.1**, which limits adjacent
span ratios to:

\[
\frac{L_i}{L_j} \leq 1.2
\]

To comply with the standard and enable use of the simplified design method, the slab system
was revised to a **four-span configuration**, which satisfied all span ratio criteria.

{% include image-gallery.html images="SPAN_CONFIGURATION_IMAGE_URL" height="450" %}
*Span configuration adjustment to satisfy NZS 3101 requirements*

---

## Structural Load Assessment

### **Dead Load (G)**
- Self-weight of slab:
\[
G_{slab} = 25 \, \text{kN/m}^3 \times 0.13 = 3.25 \, \text{kPa}
\]
- Finishes and superimposed dead load:
\[
G_{finishes} = 0.50 \, \text{kPa}
\]

\[
\boxed{G = 3.75 \, \text{kPa}}
\]

### **Live Load (Q)**
Residential occupancy (NZS 1170.1):

\[
\boxed{Q = 1.5 \, \text{kPa}}
\]

### **Ultimate Limit State Load**
\[
W = 1.2G + 1.5Q
\]
\[
W = 1.2(3.75) + 1.5(1.5) = \boxed{6.75 \, \text{kPa}}
\]

---

## Bending Moment Analysis
Bending moments were calculated using the **simplified moment coefficients** provided in
NZS 3101 for continuous one-way slabs.

### **Positive Bending Moment**
\[
M^+ = \frac{W L^2}{11}
\]
\[
M^+ = \frac{6.75 \times 3.4^2}{11} = \boxed{7.09 \, \text{kN·m/m}}
\]

### **Negative Bending Moment**
\[
M^- = \frac{W L^2}{10} = \boxed{7.80 \, \text{kN·m/m}}
\]

{% include image-gallery.html images="BENDING_MOMENT_IMAGE_URL" height="500" %}
*Positive and negative bending moment envelopes*

---

## Reinforcement Design

### **Effective Depth**
\[
d = 130 - 45 - \frac{20}{2} = \boxed{75 \, \text{mm}}
\]

### **Required Steel Area**
Reinforcement ratios were calculated using:

\[
\rho = \frac{M^*}{\phi \cdot 0.925 \cdot b \cdot d^2 \cdot f_y}
\]

Minimum reinforcement requirements were checked in accordance with **NZS 3101 Clause 9.3.8**.

### **Final Reinforcement Selection**

| Location | Design Moment (kN·m/m) | Reinforcement |
|--------|------------------------|---------------|
| End spans (+/–) | 7.09 | D12 @ 260 mm |
| Interior supports | 7.80 | D16 @ 260 mm |
| Shrinkage & temperature | — | D10 @ 390 mm |

{% include image-gallery.html images="REINFORCEMENT_DETAIL_IMAGE_URL" height="500" %}
*Reinforcement detailing and bar layout*

---

## Shear Capacity Check
Maximum design shear:

\[
V^* = 13.19 \, \text{kN}
\]

Concrete shear capacity:

\[
\phi V_c = 46.86 \, \text{kN}
\]

\[
\boxed{V^* < \phi V_c \Rightarrow \text{Shear reinforcement not required}}
\]

This confirmed that the slab thickness and reinforcement arrangement were adequate for
shear without additional stirrups.

---

## Durability & Exposure Considerations
The site was classified as **B2 exposure** due to proximity to the coastline
(approximately 484 m).

- **Minimum cover required:** 45 mm  
- **Durability design life:** 50 years  

All detailing complies with **NZS 3101 durability provisions** for coastal exposure.

---

## Engineering Design Conclusion
A **130 mm reinforced concrete one-way slab** was successfully designed using the simplified
method in NZS 3101.

**Design Justification:**
1. All ULS bending and shear demands satisfied  
2. Span configuration compliant with code limits  
3. Reinforcement exceeds minimum strength and durability requirements  
4. No shear reinforcement required  
5. Practical, buildable detailing achieved  

This project demonstrates the application of reinforced concrete theory, structural
code interpretation, and engineering judgement to produce a safe and efficient slab
design suitable for residential construction.

