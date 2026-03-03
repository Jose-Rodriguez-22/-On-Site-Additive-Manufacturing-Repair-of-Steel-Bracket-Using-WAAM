# -On-Site-Additive-Manufacturing-Repair-of-Steel-Bracket-Using-WAAM

### Sequential Thermal-Structural Simulation of Defect Restoration

---

## 📌 Project Overview

This project investigates the feasibility of using Wire Arc Additive Manufacturing (WAAM) to repair a high-stress stainless steel bracket subjected to mechanical loading in pump applications.

A sequential thermal–structural finite element analysis was conducted in ANSYS to compare:

1. Defect-free bracket
2. Bracket with crack/defect
3. Bracket repaired using WAAM (Element Birth & Death)

The study quantifies the structural improvement after additive repair and evaluates stress redistribution, deformation, and strain reduction.

---

## 🎯 Objective

- Simulate mechanical loading of a stainless steel bracket under 1000 N forces
- Evaluate stress concentration in defect region
- Model WAAM repair using moving heat flux
- Apply element birth and death to simulate deposition
- Compare structural performance before and after repair

---

## 🛠 Software & Tools

- CAD: SolidWorks
- Simulation: ANSYS Mechanical 2024
- Analysis Types:
  - Transient Thermal (Moving Heat Flux)
  - Static Structural
  - Sequentially Coupled Thermal–Structural

---

## 📐 Geometry & Loading Conditions

- Application: Pump bracket support
- Load Case: 1000 N inward force on each face
- Boundary Conditions:
  - 6 bolt locations fully constrained (all DOF restricted)
- Pressure Applied: -100 MPa (ramped loading)

Three cases analyzed:

1️⃣ Defect-Free Bracket  
2️⃣ Bracket with Crack/Defect  
3️⃣ Bracket Repaired via WAAM  

---

## 🔬 Material Properties

**Stainless Steel 316**

- Young’s Modulus: 193 GPa
- Yield Strength: 502 MPa
- Ultimate Strength: 860 MPa
- Melting Point: 1375–1400 °C
- Poisson’s Ratio: 0.30–0.31

Selected for high weldability and suitability for WAAM deposition.

---

## 🌡 Thermal Simulation Setup (WAAM Process)

- Moving Heat Flux: 100 W/mm²
- Travel Speed: 1 mm/s
- Deposition Temperature: 1350 °C
- Simulation Time: 50 seconds
- 200 time steps
- Element Birth & Death used for progressive deposition
- Convection applied for environmental heat loss

Heat source localized along defect region.

---

## 🧱 Structural Analysis Setup

- Temperature imported from transient thermal results
- Bonded contact between deposited material and bracket
- Fixed constraints at bolt locations
- Large deformation enabled
- Load maintained consistent across all cases

---

## 📊 Results Comparison

| Metric | Defect-Free | With Defect | After WAAM Repair |
|--------|------------|-------------|-------------------|
| Equivalent Stress | 2535 MPa | 2750 MPa | 77 MPa |
| Normal Stress | 1262 MPa | 1380 MPa | 48 MPa |
| Total Deformation | 0.76 mm | 0.8716 mm | 0.01976 mm |

### 🔥 Stress Reduction Achieved

- Equivalent Stress ↓ ~97%
- Normal Stress ↓ ~96%
- Significant deformation reduction

The repaired geometry redistributed stress effectively and eliminated sharp stress concentrators.

---

## 🧠 Engineering Insights

- Crack geometry amplified stress concentrations beyond yield limits
- WAAM deposition smoothed sharp notch regions
- Added material improved load transfer path
- Heat-affected zone properly captured via transient modeling
- Post-repair stresses dropped well below yield strength

This simulation demonstrates that additive repair can not only restore but significantly enhance structural integrity.

---

## 🏗 Manufacturing & Industrial Relevance

This project highlights:

- On-site additive repair capability
- Reduced waste vs full component replacement
- Lifecycle extension of high-value industrial parts
- Sustainable manufacturing strategy
- Application of WAAM in structural repair

The results support AM repair as a viable alternative to part replacement in high-stress components.

---

## 🚀 Key Competencies Demonstrated

- WAAM process simulation
- Moving heat flux modeling
- Element Birth & Death technique
- Sequential coupled FEA
- Stress concentration analysis
- Structural validation post-repair
- Quantitative performance comparison

---

## 📎 Author

Jose Rodriguez  
Mechanical Engineering – University of Texas at Dallas  
Specialization: Additive Manufacturing & Structural Simulation  

📧 jmr180004@utdallas.edu  
🔗 LinkedIn: https://www.linkedin.com/in/jose-m-rodriguez-/
