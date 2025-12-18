# High-Speed PCB Design Portfolio

## 📌 Overview
This repository is a **professional portfolio of high-speed PCB design projects** with a strong
focus on **Signal Integrity (SI)**, **Power Integrity (PI)**, and **EMI-aware PCB layout practices**.

All projects in this repository are **designed using Altium Designer** and span
**2-layer to 6-layer PCBs**, covering both fundamental and advanced high-speed design challenges.

This repository is intended to demonstrate **engineering decision-making**, not just PCB artwork.

---

## 🎯 Objectives
The primary objectives of this repository are to:
- Showcase practical high-speed PCB design skills
- Demonstrate controlled impedance routing techniques
- Document SI/PI-related design decisions
- Highlight real-world constraints such as fabrication limits and EMI considerations
- Serve as a technical reference for interviews and professional evaluations

---

## ⚙️ Design Scope
Projects included in this repository cover:

- PCB layer counts: **2-layer, 4-layer, and 6-layer**
- High-speed digital signals operating in the MHz–GHz range
- Controlled impedance routing (single-ended & differential)
- Transmission line effects and reflections
- Signal termination techniques:
  - Series termination
  - π termination
  - T termination
- Length matching and skew control
- Return current path continuity
- Power Delivery Network (PDN) design
- EMI and noise mitigation strategies

---

## 🧠 Design Methodology
Each project follows a structured, engineering-driven workflow:

1. Define electrical and interface requirements
2. Select appropriate PCB stackup
3. Calculate trace impedance and geometry
4. Choose termination and routing strategies
5. Implement SI/PI-aware PCB layout
6. Review EMI-critical areas
7. Generate manufacturing outputs
8. Validate design through testing or analysis
9. Document lessons learned

---

## 🛠 Tools & Standards
- **EDA Tool:** Altium Designer
- **PCB Materials:** FR4 (unless otherwise specified)
- **Reference Standards:**
  - IPC-2221 (Generic PCB Design)
  - IPC-2141 (Controlled Impedance)
- **Technical References:**
  - Howard Johnson – *High-Speed Digital Design*
  - Eric Bogatin – *Signal and Power Integrity*
  - Semiconductor vendor layout guidelines (TI, ADI, NXP, ST)

---

## 🧩 Stackup & Layer Complexity
| PCB Type | Description |
|--------|-------------|
| 2-Layer | Fundamental high-speed routing under tight constraints |
| 4-Layer | Dedicated reference planes for controlled impedance |
| 6-Layer | Advanced SI/PI isolation and EMI control |

Each stackup selection is justified and documented within the project folders.

---

## 📂 Repository Structure
Each project in this repository includes:

- **Design Requirements**
- **Schematics & PCB Layout (Altium)**
- **Stackup and Impedance Calculations**
- **Signal Integrity Analysis**
- **Power Integrity Strategy**
- **EMI / EMC Considerations**
- **Manufacturing Outputs (Gerbers, Drill Files)**
- **Testing & Validation (where applicable)**
- **Design Decisions & Lessons Learned**

This ensures full traceability from requirements to final PCB.

---

## 📐 Signal Integrity Focus
Signal integrity considerations documented in this repository include:
- Impedance matching and termination placement
- Reflection and ringing mitigation
- Crosstalk reduction techniques
- Length matching and skew control
- Return current path optimization
- Edge-rate control for EMI reduction

---

## 🔋 Power Integrity Focus
Power integrity practices include:
- Local and bulk decoupling strategies
- PDN impedance reduction
- Grounding and via stitching techniques
- Minimizing high-current loop areas

---

## 🧪 Testing & Validation
Where hardware is available, validation includes:
- Oscilloscope-based signal quality measurements
- Reflection and ringing observation
- Comparison of pre- and post-fix signal behavior

Measurement setup and observations are documented.

---

## 📘 Lessons Learned
Each project contains a **Lessons Learned** section documenting:
- Design challenges encountered
- Issues identified during review or testing
- Improvements planned for future revisions

This reflects real-world engineering practice and continuous improvement.

---

## 📚 References
A dedicated reference section includes:
- Application notes
- Industry standards
- Textbooks and professional resources used during design

---

## 👤 Author
**Harsh Saini**  
Hardware & PCB Design Engineer  

---

## 🚀 Repository Status
This repository is actively maintained and will continue to grow
as new high-speed PCB projects are added and existing designs are refined.
