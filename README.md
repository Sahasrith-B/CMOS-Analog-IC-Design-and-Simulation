# CMOS Analog IC Design & Simulation  
**Cadence Virtuoso | Spectre | SCL 180 nm CMOS**

## Overview
This repository documents a series of **Design Modules** completed as part of a **CMOS Analog IC Design** project under the guidance of **Prof. Tarun Kumar Agarwal**.

Each design module is provided as a **self-contained PDF report** and covers both **analytical calculations** and **Cadence Virtuoso simulations**. The work progresses from **MOSFET device characterization** to **multi-stage and fully differential amplifier design**, with strong emphasis on **biasing, stability, and frequency response**.

---

## Tools & Technology
- **EDA Tool:** Cadence Virtuoso (Spectre Simulator)  
- **CMOS Technology:** SCL 180 nm  
- **Design Methodologies:**
  - Square-law MOSFET modeling
  - Small-signal analysis
  - gm/Id based transistor sizing
- **Analyses Performed:**
  - DC operating point
  - AC analysis (gain, bandwidth, phase margin)
  - Transient response
  - Output impedance and saturation verification

---

## Design Modules

### **Design Module 01: DC Characteristics & Small-Signal Analysis**
- NMOS and PMOS transfer and output characteristics
- Extraction of threshold voltage, gm, gds, and channel-length modulation
- Study of device behavior with variation in channel length and width
- Small-signal parameter analysis and interpretation

📄 *Report:* `Design_Module_01_DC_Characteristics.pdf`

---

### **Design Module 02: Bias Circuits & Current Mirrors**
- Design of simple and cascode current mirrors
- Output compliance and saturation analysis
- Comparison of current accuracy and output impedance
- Study of channel-length modulation effects

📄 *Report:* `Design_Module_02_Biasing_and_Current_Mirrors.pdf`

---

### **Design Module 03: Single-Stage Amplifier**
- Common-source amplifier design and biasing
- DC operating point verification
- Voltage gain and power consumption analysis
- Ensuring saturation of all devices

📄 *Report:* `Design_Module_03_Single_Stage_Amplifier.pdf`

---

### **Design Module 04: Cascode Amplifier**
- Cascode amplifier topology for enhanced gain
- Biasing strategy for cascode devices
- AC gain and frequency response analysis
- Power consumption estimation and comparison with single-stage amplifier

📄 *Report:* `Design_Module_04_Cascode_Amplifier.pdf`

---

### **Design Module 05: Operational Transconductance Amplifier (OTA)**
- Single-stage OTA design
- DC gain and transconductance evaluation
- Bias optimization and power analysis
- Verification of proper region of operation

📄 *Report:* `Design_Module_05_OTA_Design.pdf`

---

### **Design Module 06: OTA with Feedback Network**
- OTA integrated with resistive feedback
- Closed-loop gain analysis
- Stability and bandwidth evaluation
- Comparison of open-loop and closed-loop behavior

📄 *Report:* `Design_Module_06_OTA_With_Feedback.pdf`

---

### **Design Module 07: Two-Stage OTA**
- Mathematical modeling and small-signal analysis
- Transistor sizing using square-law and gm/Id methodology
- Frequency compensation for stability
- Extraction of gain, GBW, and phase margin

📄 *Report:* `Design_Module_07_Two_Stage_OTA.pdf`

---

### **Design Module 08: Fully Differential Amplifier**
- Analytical design using square-law and gm/Id methodology
- Differential operation and biasing strategy
- Design trade-offs between gain, output swing, and power

📄 *Report:* `Design_Module_08_Fully_Differential_Amplifier.pdf`

---

## Key Skills Demonstrated
- CMOS analog circuit design from **device to block level**
- Transistor sizing and bias optimization
- Stability analysis and frequency compensation
- Interpretation of gain–bandwidth–power trade-offs
- Professional use of **Cadence Virtuoso & Spectre**

---


## Notes
- All designs were simulated in **Cadence Virtuoso (Spectre)**
- Operating regions were verified for all transistors
- Each PDF contains schematics, simulation plots, and detailed explanations

---

⭐ *If you find this repository useful, consider starring it.*
