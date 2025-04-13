# 🎛️ 9Th Order Chebyshev Low Pass Filter Design  
**Cut-off Frequency: 9 kHz | Passband Ripple: 3 dB**  

<div align="center">
  <img src="https://img.shields.io/badge/Order-9th-blue" alt="Filter Order">
  <img src="https://img.shields.io/badge/Cutoff-9kHz-green" alt="Cutoff Frequency">
  <img src="https://img.shields.io/badge/Ripple-3dB-yellow" alt="Passband Ripple">
</div>

---

## 📖 Preface  
Chebyshev filters are widely used in modern electronics for their sharp frequency transitions with controlled passband ripple. This project implements a **9th-order Chebyshev low-pass filter** with:  
- **9 kHz cut-off frequency**  
- **3 dB passband ripple**  
- Practical simulation and PCB implementation  

Key learning outcomes include hands-on experience with:  
✔ Filter design theory  
✔ Proteus simulation  
✔ PCB layout techniques  
✔ Frequency response analysis  

---

## 🖥️ Design Implementation  

### Proteus Circuit Design  
<div align="center">
  <img src="https://github.com/Deshan-Lokuge01/Filter-Designing/raw/main/Proteus_Sketch.jpg" width="600" alt="Proteus Schematic">
</div>

### Simulation Results  
<div align="center">
  <img src="https://github.com/Deshan-Lokuge01/Filter-Designing/raw/main/Simulation_Results.jpg" width="600" alt="Frequency Response Simulation">
  
  **Key Measurements at Cursor Point:**  
   Frequency: 9.13 kHz  
   Gain: -3.04 dB  
   Test Conditions:  
   Sine wave (Vpp = 10V, f = 1 kHz)  
   Supply: ±12V  
</div>

---

## 🛠️ Hardware Implementation  

### PCB Layout  
<div align="center">
  <img src="https://github.com/Deshan-Lokuge01/Filter-Designing/raw/main/PCB_Layout.jpg" width="500" alt="PCB Design">
</div>

### Physical Implementation  
<div align="center">
  <img src="https://github.com/Deshan-Lokuge01/Filter-Designing/raw/main/PCB_Implimentation.jpg" width="500" alt="Built PCB">
</div>

### Spectrum Analyzer Results  
<div align="center">
  <img src="https://github.com/Deshan-Lokuge01/Filter-Designing/raw/main/Spectrum_Analyzer_Results.jpg" width="600" alt="Frequency Spectrum">
</div>

---

## 🔍 Discussion  
**Observed Behavior:**  
- Achieved bandwidth: ~30 kHz (vs designed 9 kHz)  

**Potential Causes:**  
1. Parasitic capacitance from PCB trace clearance  
2. Component value tolerances  
3. Non-ideal op-amp characteristics  

**Improvement Opportunities:**  
- Precision component measurement  
- Ground plane optimization  
- SPICE model verification  

---
