# 🔎 Concealed Leak Localization

### Non-Invasive Localization of Concealed Water Leaks in Non-Metallic Indoor Pipelines

**Project Stage:** Phase 1 — Customer & Problem Validation  
**Domain:** Manufacturing & Automation

---

## 📌 Overview

Concealed water leaks can occur inside walls, beneath floors, or within other inaccessible sections of a building's plumbing system.

The challenge is not always detecting that a leak exists. A more difficult problem can be **accurately locating the actual source of a small concealed leak** when the pipeline cannot be directly observed.

Water may travel through surrounding materials before becoming visible, so the location of visible dampness may not correspond to the actual leak source.

This project investigates the problem of **accurately localizing concealed leaks in non-metallic indoor pipelines such as PVC and PEX**, while minimizing unnecessary structural opening.

> **Current status:** The project is in the problem-validation stage. Primary-user evidence is being sought before finalizing the technical solution.

---

## 🎯 Problem Statement

> **Leak-detection technicians face difficulty accurately localizing small concealed water leaks in non-metallic indoor pipelines, potentially leading to repeated investigation or unnecessary structural opening to identify the actual leak source.**

### In Simple Terms

The project focuses on:

> **"We know there is a leak — but where exactly is it?"**

The goal is not simply to detect the presence of a leak, but to help determine its **probable location** with greater confidence.

---

## 👤 Who Has the Problem?

### Primary Users

- Leak-detection technicians
- Professional plumbers

### Other Stakeholders

- Plumbing contractors
- Facility maintenance teams
- Property managers
- Building maintenance teams
- Homeowners and occupants

### Primary User Need

> **Locate the concealed leak accurately while minimizing unnecessary wall or floor opening.**

---

## 🔍 Why Is Localization Difficult?

Several factors can make concealed-leak localization challenging:

- The pipeline cannot be directly observed.
- Water can migrate through surrounding materials.
- Visible dampness may appear away from the actual leak.
- Small leaks may produce weaker diagnostic signals.
- Non-metallic pipe materials have different signal-transmission characteristics.
- Pipe depth and installation geometry can affect measurements.
- Background noise and environmental conditions can interfere with detection.
- Sensor placement can influence diagnostic results.

Therefore, the project is focused specifically on the **localization gap**, rather than simply detecting whether water is present.

---

## 🛠️ Existing Approaches

Existing technologies can already be used for concealed leak investigation.

### Acoustic Leak Detection

Uses sound or vibration associated with escaping water.

**Limitation:** Performance can vary with pipe material, leak characteristics, pressure, sensor placement, and background noise.

### Thermal Imaging

Identifies temperature differences associated with moisture or water movement.

**Limitation:** Effectiveness depends on thermal contrast, surface conditions, leak characteristics, and depth.

### Moisture Detection

Identifies areas with elevated moisture levels.

**Limitation:** The wet area may not correspond directly to the original pipe failure location.

### Pressure / Flow Monitoring

Identifies abnormal pressure or flow behaviour.

**Limitation:** Can indicate that a leak exists but may not directly provide its exact physical location.

### Tracer-Gas Methods

Use a detectable gas to identify possible leakage locations.

**Limitation:** Requires suitable equipment, procedures, and operating conditions.

---

## ⚠️ Problem Gap Being Investigated

This project does **not** assume that existing leak-detection technologies are ineffective.

Instead, it investigates:

> **Under what real-world conditions do existing methods struggle to confidently localize small concealed leaks in non-metallic indoor pipelines?**

The project will examine factors such as:

- Leak size
- Pipe material
- Pipe depth
- Installation conditions
- Environmental interference
- Sensor placement
- Diagnostic workflow
- Technician confidence in the result

The significance of this gap still needs to be validated through **primary-user research**.

---

## 🧪 Current Problem Hypothesis

> **Leak-detection technicians may struggle to confidently localize small concealed leaks in non-metallic indoor pipelines under certain site conditions, leading to repeated investigation or potentially unnecessary structural opening.**

This is currently a **problem hypothesis**, not a fully validated claim.

---

## 👥 Customer Validation

The next stage of the project focuses on understanding the actual technician workflow and determining whether the problem is frequent, significant, and worth solving.

### Planned User Groups

| User Group | Purpose |
|---|---|
| Leak-detection technicians / plumbers | Understand real diagnostic difficulties |
| Maintenance staff | Understand maintenance workflow |
| Plumbing contractors | Understand practical and business constraints |
| Facility / property managers | Understand impact and decision-making |

### Key Questions

- How are concealed leaks currently located?
- Which cases are difficult to diagnose?
- How often does exact localization remain uncertain?
- Which existing methods are used?
- When is a second method required?
- When does structural opening become necessary?
- What causes uncertainty?
- What information would help technicians make better decisions?
- Would a portable localization tool be useful?
- What would make technicians trust such a tool?

---

## 🏭 Why Manufacturing & Automation?

The project fits the Manufacturing & Automation domain through:

- **Sensing** — capturing physical signals from a concealed system
- **Signal acquisition** — collecting sensor measurements
- **Signal interpretation** — identifying meaningful leak-related information
- **Fault diagnosis** — determining whether a fault is present
- **Fault localization** — estimating the probable fault location
- **Condition monitoring** — assessing the condition of inaccessible infrastructure
- **Maintenance support** — assisting technicians during diagnosis and repair

The intended system is therefore a **sensor-based diagnostic and maintenance-support system**.

---

## 💡 Potential Phase 2 Directions

No final technology has been selected yet.

Possible directions include:

### 1. Multi-Point Acoustic Localization

Use multiple contact sensors to capture leak-related vibrations at different positions and estimate the probable leak location.

### 2. Hybrid Signal Localization

Combine complementary measurements such as acoustic, pressure, flow, or other suitable signals to improve localization confidence.

### 3. Guided Diagnostic Scanner

Develop a portable tool that scans a suspected region and helps identify areas with a higher probability of leakage.

The final concept will be selected only after validating the user need and comparing technical feasibility.

---

## 🎯 Potential Success Measures

A future prototype could be evaluated using:

- **Localization accuracy**
- **Reduction in investigation area**
- **Diagnostic time**
- **Repeatability**
- **Technician usability**
- **Technician confidence**
- **Reduction in unnecessary structural opening**

---

## ⚠️ Key Technical Risk

The primary technical risk is:

> **A sensing approach may not provide sufficiently reliable localization under realistic PVC/PEX installation conditions.**

Performance may depend on:

- Leak size
- Pipe material
- Pipe depth
- Water pressure
- Surrounding structure
- Sensor placement
- Background noise
- Installation geometry

Therefore, the project will validate the sensing approach experimentally rather than assuming a particular sensor or AI method will work.

---

## 🤖 Role of AI

AI/ML is **not a mandatory component** of the project.

It may be considered later if the collected signals are sufficiently complex and conventional signal-processing methods are not adequate.

The initial focus is on:

> **Sensing → Signal Processing → Localization**

rather than forcing AI into the solution.

---

## 🗺️ Project Roadmap

```text
Phase 1 — Problem Validation
        ↓
Customer & Technician Interviews
        ↓
Current Workflow Mapping
        ↓
Problem Validation
        ↓
Technical Requirements
        ↓
Phase 2 — Concept Development
        ↓
Compare Technical Approaches
        ↓
Select Concept
        ↓
Prototype Development
        ↓
Controlled Testing
        ↓
Localization Performance Evaluation
        ↓
Iteration & Improvement
        ↓
Realistic / Field Testing
