---
layout: post
title: Reinforced Concrete Slab Design – Structural Design Assignment
date: 2024-05-01
description: >
  Individual reinforced concrete slab design project involving load assessment,
  ultimate limit state analysis, bending and shear checks, and reinforcement sizing
  in accordance with relevant design standards.
skills:
  - Structural load assessment
  - Ultimate limit state design
  - Reinforced concrete design
  - Bending moment analysis
  - Reinforcement sizing
  - Engineering calculations
main-image: /slab-design-main.jpg
---

🔗 **[CLICK HERE TO VIEW FULL STRUCTURAL DESIGN REPORT (PDF)](PASTE_GOOGLE_DRIVE_LINK_HERE){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
This individual project focused on the **structural design of a reinforced concrete slab**
using first-principles engineering calculations. The objective was to determine the
governing design actions, bending moments, and required reinforcement under **ultimate
limit state (ULS)** conditions, while ensuring compliance with strength and serviceability
requirements.

The project emphasised clear derivation of actions, correct use of notation, and
verification of structural capacity through calculation-based checks.

---

## Structural System & Assumptions
- **Structural element:** One-way reinforced concrete slab  
- **Span length:** 4.5 m  
- **Slab thickness:** 150 mm  
- **Concrete density:** 24 kN/m³  
- **Steel yield strength:** f<sub>y</sub> = 500 MPa  
- **Strength reduction factor:** φ = 0.85  

{% include image-gallery.html images="SLAB_LAYOUT.jpg, LOAD_PATH_DIAGRAM.jpg" height="450" %}
*Slab geometry and load distribution*

---

## Design Actions

### Permanent Actions (G)
Self-weight of slab:

\[
w_G = \gamma_c \times t
\]

\[
w_G = 24 \times 0.15 = 3.60 \, \text{kN/m}^2
\]

Including finishes:

\[
w_G = 4.60 \, \text{kN/m}^2
\]

---

### Imposed Actions (Q)

\[
w_Q = 3.0 \, \text{kN/m}^2
\]

---

## Ultimate Limit State Load Combination

\[
w^* = 1.2G + 1.5Q
\]

\[
w^* = 1.2(4.60) + 1.5(3.0)
\]

\[
w^* = 10.02 \, \text{kN/m}^2
\]

---

## Bending Moment Analysis
For a simply supported one-way slab:

\[
M^* = \frac{w^* L^2}{8}
\]

\[
M^* = \frac{10.02 \times 4.5^2}{8}
\]

\[
M^* = 25.4 \, \text{kN·m/m}
\]

{% include image-gallery.html images="BENDING_MOMENT_DIAGRAM.jpg" height="400" %}
*Governing bending moment at mid-span*

---

## Effective Depth Calculation

\[
d = h - c - \frac{\phi}{2}
\]

\[
d = 150 - 30 - 6 = 114 \, \text{mm}
\]

Lever arm:

\[
z = 0.9d = 102.6 \, \text{mm}
\]

---

## Required Tensile Reinforcement

\[
A_{s,req} = \frac{M^*}{\phi f_y z}
\]

\[
A_{s,req} =
\frac{25.4 \times 10^6}
{0.85 \times 500 \times 102.6}
\]

\[
A_{s,req} = 582 \, \text{mm}^2/\text{m}
\]

---

## Provided Reinforcement
Selected reinforcement layout:

- **N12 bars @ 200 mm centres**

\[
A_{s,prov} =
\frac{113 \times 1000}{200}
\]

\[
A_{s,prov} = 565 \, \text{mm}^2/\text{m}
\]

\[
A_{s,prov} \approx A_{s,req}
\quad \Rightarrow \quad \text{OK}
\]

---

## Moment Capacity Check

\[
\phi M_n = \phi A_s f_y z
\]

\[
\phi M_n =
0.85 \times 565 \times 500 \times 102.6
\]

\[
\phi M_n = 24.6 \, \text{kN·m/m}
\]

\[
\phi M_n \ge M^*
\quad \Rightarrow \quad \text{Bending capacity satisfied}
\]

---

## Shear Capacity Check

\[
V^* = \frac{w^* L}{2}
\]

\[
V^* = \frac{10.02 \times 4.5}{2}
\]

\[
V^* = 22.55 \, \text{kN/m}
\]

Concrete shear resistance:

\[
\phi V_n > V^*
\quad \Rightarrow \quad \text{Shear capacity adequate}
\]

---

## Engineering Conclusion
The reinforced concrete slab design satisfies **ultimate limit state requirements**
for bending and shear. The selected reinforcement layout provides sufficient strength
while maintaining constructability and material efficiency.

This project demonstrates:
- Correct derivation of design actions  
- Clear application of ULS load combinations  
- Reinforcement sizing based on first principles  
- Verification of structural capacity through calculation  

