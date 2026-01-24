---
layout: post
title: Foundation Engineering Design - 4-Story Apartment Building
date: 2025-06-06
description: >
  Comprehensive geotechnical analysis and foundation design for a 4-story concrete 
  apartment building, including load calculations, settlement analysis, and seismic design.
skills:
  - Structural load analysis
  - Shallow foundation design
  - Pile foundation analysis
  - Settlement calculations
  - Seismic design
  - Retaining wall design
  - NZ standards compliance
main-image: /foundation-main4.jpg
---

🔗 **[CLICK HERE TO VIEW FULL FOUNDATION ENGINEERING REPORT (PDF)](https://drive.google.com/file/d/1oKcrDK8BtXqQaG2SIB8vm-XK_d20wdxt/view?usp=sharing){:target="_blank" rel="noopener noreferrer"}**

---

## Project Overview
Complete foundation engineering design for a 4-story concrete apartment building at 14 Liberation Road, Papakura. The project included comprehensive geotechnical analysis, structural load calculations, and foundation system optimization meeting NZS standards.

**Key Design Decisions:**
- **Selected Foundation:** Shallow isolated pad footings (1.5m × 1.5m)
- **Total Building Area:** 640m² (4 floors)
- **Soil Type:** Clayey SILT with organic inclusions (OL classification)
- **Groundwater Level:** 1.75m depth

{% include image-gallery.html images="https://i.ibb.co/WpDJj8dg/FLOOR-PLAN-IMAGE.png, https://i.ibb.co/RT8gDSPV/Screenshot-2026-01-24-110501.png" height="500" %}
*Structural floor plan and load distribution analysis*

---

## Technical Calculations & Analysis

### **Structural Load Analysis**
Using NZS 1170.1 standards:
- **Dead Load:** 6.50 kN/m² (concrete slab, finishes, partitions)
- **Live Load:** 1.5 kN/m² (residential occupancy)
- **ULS Load per Floor:** 1,608 kN (1.2G + 1.5Q)
- **Total Building Load:** 6,432 kN distributed to 9 columns
- **Column Load:** 625.33 kN each

### **Shallow Foundation Design (Selected Solution)**
**Meyerhof Bearing Capacity Analysis:**
- φ' = 27°, c' = 25 kN/m², γ = 16 kN/m³
- q<sub>u</sub> = 1,906.75 kN/m²
- FoS = q<sub>u</sub>/q<sub>applied</sub> = **3.04** (NZS 3604 requires ≥3.0)
- q<sub>applied</sub> = 277.92 kN/m²
- Q<sub>allowable</sub> = 1,430.06 kN > 625.33 kN ✓

### **Settlement Analysis**
**Total Settlement = 2.42 cm** (within 2.5 cm NZS 3604 limit):
- Elastic Settlement: 1.24 cm (incl. groundwater effect)
- Primary Consolidation: 1.13 cm
- Secondary Consolidation: 0.05 cm

{% include image-gallery.html images="https://i.ibb.co/WvDM8gn9/SOIL-PROFILE-TABLE-IMAGE.png" height="500" %}
*Geotechnical soil parameters and classification*

---

## Alternative Solutions Analyzed

### **Pile Foundation Design**
- **400mm diameter bored piles** to 15m depth
- **Ultimate Capacity:** 2,591.27 kN
- **Allowable Capacity:** 863.76 kN > 625.33 kN ✓
- **Settlement:** 34.42 mm < 40 mm (0.1D limit) ✓

### **Retaining Wall Design**
- **Cantilever concrete wall** for 4m slope
- **Seismic Design:** Z factor < 0.15 (Auckland region)
- **Drainage System:** Weep holes + DN110 Nexus Hiway pipes
- **Risk Mitigation:** Geotextile filters and waterproof membrane

{% include image-gallery.html images="https://i.ibb.co/PvbPQY0T/RETAINING-WALL-DRAWING-IMAGE.png, https://i.ibb.co/ZpBffRcy/RETAINING-WALL-SITE-IMAGE.png" height="550" %}
*Technical retaining wall details and site implementation*

---

### **Terzaghi Bearing Capacity Analysis (Comparative Method)**
For design verification, Terzaghi's classical bearing capacity equation was analyzed for comparison:

**Terzaghi Equation for Square Foundations:**  
q_ult = 1.3cN_c + qN_q + 0.4γBN_γ

**Calculation with φ' = 27°:**  
- Bearing Capacity Factors: N_c = 23.94, N_q = 13.20, N_γ = 14.47  
- c = 25 kN/m², q = 24 kN/m², B = 1.5m, γ = 16 kN/m³  

q_ult = 1.3 × 25 × 23.94 + 24 × 13.20 + 0.4 × 16 × 1.5 × 14.47  
q_ult = 778.05 + 316.80 + 138.91  
q_ult = 1,233.76 kN/m²  

**Safety Factor Comparison:**  
- **Terzaghi Method:** FoS = 1,233.76 / 277.92 = **4.44** (more conservative)  
- **Meyerhof Method:** FoS = **3.04** (more realistic for square foundations)  

**Design Justification:** The Meyerhof method was selected as it accounts for foundation shape factors and depth effects more accurately for square footings, providing a more realistic safety factor while still exceeding NZS 3604 requirements.

{% include image-gallery.html images="https://i.ibb.co/GvVSr7Tb/terzaghi.jpg" height="300" %}
*Terzaghi bearing capacity factors and equation reference*

---

## Engineering Design Conclusion
**Shallow isolated pad footings** were selected as the optimal solution based on comprehensive analysis:

**Technical Justification:**
1. **Adequate Safety Margin:** FoS = 3.04 exceeds NZS 3604 requirements
2. **Settlement Compliance:** 2.42 cm total settlement within 2.5 cm limit
3. **Cost Efficiency:** ~40% cost reduction compared to pile foundations
4. **Constructability:** Simplified construction sequencing
5. **Groundwater Managed:** Temporary dewatering during construction

**Final Design Specifications:**
- **Foundation Type:** Isolated pad footings (1.5m × 1.5m)
- **Depth:** 1.5m below ground level
- **Column Load Capacity:** 625.33 kN each
- **Settlement:** 2.42 cm (well within limits)
- **Retaining Wall:** Cantilever design with comprehensive drainage

This project demonstrates practical application of geotechnical engineering principles, rigorous calculation methodology, and evidence-based design optimization for real-world construction.
