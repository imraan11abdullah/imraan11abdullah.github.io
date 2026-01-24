---
title: "Reinforced Concrete One-Way Slab Design"
date: 2025-05-02
layout: project
---

## 📌 Project Overview

This project presents the **structural analysis and design of a reinforced concrete one-way slab system** for a two-storey residential building located in **Ākitio, New Zealand**.  
The design was completed **individually** and follows the requirements of:

- **NZS 3101:2006** – Concrete Structures Standard  
- **NZS 1170.0 & NZS 1170.1** – Structural Design Actions  

The slab system was designed using the **simplified method** permitted under NZS 3101, with checks carried out for strength, serviceability, durability, and constructability.

---

## 🏗️ Structural System

- Structural form: **Moment-resisting frame**
- Slab type: **Reinforced concrete one-way slab**
- Design working life: **50 years**
- Concrete strength: **30 MPa**
- Reinforcement grade: **300E**

![Floor Plan](../assets/rc-one-way-slab/floor-plan.png)

---

## 📐 One-Way Slab Configuration

Initial assessment showed that a **3-span configuration did not satisfy** the simplified method span ratio requirements:

\[
\frac{L_i}{L_j} \leq 1.2 \quad \text{(NZS 3101: Clause 6.7.2.1.1)}
\]

The layout was therefore revised to a **4-span configuration**, which satisfied all span ratio criteria and allowed the use of the simplified design approach.

![Slab Spans](../assets/rc-one-way-slab/slab-spans.png)

---

## ⚖️ Load Assessment

### Dead Load (G)

\[
G = 25 \, \text{kN/m}^3 \times 0.13 \, \text{m} = 3.25 \, \text{kPa}
\]

Including finishes:

\[
G = 3.75 \, \text{kPa}
\]

### Live Load (Q)

\[
Q = 1.5 \, \text{kPa}
\]

### Governing Load Combination (ULS)

\[
W = 1.2G + 1.5Q = 6.75 \, \text{kPa}
\]

---

## 📊 Bending Moment Analysis

Using the **NZS 3101 simplified coefficients**, bending moments were calculated for both **end spans and interior spans**.

### Positive Bending Moment (example)

\[
M^+ = \frac{W L^2}{11} = \frac{6.75 \times 3.4^2}{11} = 7.09 \, \text{kN·m/m}
\]

### Negative Bending Moment (example)

\[
M^- = \frac{W L^2}{10} = 7.80 \, \text{kN·m/m}
\]

![Bending Moments](../assets/rc-one-way-slab/bending-moment.png)

---

## 🔩 Reinforcement Design

Effective depth:

\[
d = 130 - 45 - \frac{20}{2} = 75 \, \text{mm}
\]

Required steel area was calculated using:

\[
\rho = \frac{M^*}{\phi \cdot 0.925 \cdot b \cdot d^2 \cdot f_y}
\]

Minimum reinforcement requirements were checked in accordance with **NZS 3101 Section 9.3.8**.

### Final Reinforcement Summary

| Location | Moment (kN·m/m) | Reinforcement |
|--------|----------------|--------------|
| End spans (±) | 7.09 | D12 @ 260 mm |
| Interior supports | 7.80 | D16 @ 260 mm |
| Shrinkage & temperature | — | D10 @ 390 mm |

![Reinforcement Layout](../assets/rc-one-way-slab/reinforcement-layout.png)

---

## 🧱 Durability & Exposure Classification

- Site classified as **B2 (Coastal frontage)**  
- Distance to coastline: **≈ 484 m**
- Minimum cover required:

\[
c_{min} = 45 \, \text{mm}
\]

This ensures compliance with **NZS 3101 durability provisions** for a 50-year design life.

---

## ✂️ Shear Capacity Check

Maximum design shear:

\[
V^* = 13.19 \, \text{kN}
\]

Concrete shear capacity:

\[
\phi V_c = 46.86 \, \text{kN}
\]

\[
V^* < \phi V_c \Rightarrow \text{No shear reinforcement required}
\]

![Shear Check](../assets/rc-one-way-slab/shear-check.png)

---

## ✅ Key Outcomes

- Simplified method successfully applied under NZS 3101  
- Slab thickness conservatively selected as **130 mm**  
- Reinforcement fully compliant with strength and durability requirements  
- No shear reinforcement required  
- Practical and buildable detailing achieved  

---

## 📄 Full Technical Report

**🔗 [Click here to view the full design report (PDF)](PUT-YOUR-GOOGLE-DRIVE-LINK-HERE)**

---

## 🧠 Skills Demonstrated

- Reinforced concrete design (NZS 3101)
- Load combination assessment (NZS 1170)
- Bending and shear analysis
- Engineering judgement and code compliance
- Professional technical documentation

