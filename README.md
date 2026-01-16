<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<hr/>

<p align="center">
  <strong>Electronics</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  Rectification
</h1>

<p align="center">
  <strong>Vasileios Evangelos Athanasiou</strong><br>
  Student ID: 19390005
</p>

<p align="center">
  <a href="https://github.com/Ath21" target="_blank">GitHub</a> ·
  <a href="https://www.linkedin.com/in/vasilis-athanasiou-7036b53a4/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Eleni Tsalera, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.researchgate.net/profile/Eleni-Tsalera-2" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Lecturer in Applications
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, December 2022
</p>

---

# Project Overview

The project investigates multiple rectification techniques through:
- **Theoretical analysis**
- **Computer simulation using Multisim**
- **Experimental laboratory validation**

These approaches ensure a complete understanding of rectifier operation and real-world behavior.

---

## Table of Contents

| Section | Folder / File | Description |
|--------:|---------------|-------------|
| 1 | `assign/` | Assignment material |
| 1.1 | `assign/Exercise-5th-Rectification.pdf` | Assignment description (English) |
| 1.2 | `assign/Άσκηση-5η-Ανόρθωση.pdf` | Assignment description (Greek) |
| 2 | `componentss/` | Lab components and equipment images |
| 3 | `docs/` | Theoretical documentation |
| 3.1 | `docs/Rectification.pdf` | Theory (English) |
| 3.2 | `docs/Ανόρθωση.pdf` | Theory (Greek) |
| 4 | `lab1b/` | Lab 1b: Diode conducts experiment images and Multisim file |
| 5 | `lab2a/` | Lab 2a: Diode conducts analysis images, graphs, and Multisim file |
| 6 | `lab2b/` | Lab 2b: Diode not conducts experiment images, graphs, and Multisim file |
| 7 | `lab3b/` | Lab 3b: Bridge and double rectification experiments, images, graphs, Multisim files |
| 8 | `photos-in-lab/` | Lab photos and equipment in action |
| 9 | `questions/` | Questions related to the lab |
| 10 | `README.md` | Repository overview and instructions |

---

## Core Modules

### 1. Simple Rectification with Resistance
- Mathematical analysis of half-wave rectification  
- Multisim simulation of the circuit  
- Breadboard implementation using:
  - **4.7 kΩ resistor**
  - **Silicon diode**

---

### 2. Simple Rectification with Diode-Switch (Parts A & B)
- Detailed examination of diode-switch behavior  
- Analysis of conduction and cutoff states during input signal cycles  

---

### 3. Double Rectification with Bridge
- Design and implementation of **full-wave rectification**
- Use of a **diode bridge** to utilize both half-cycles of the input waveform
- Comparison with single rectification in terms of output stability and efficiency

---

## Laboratory Equipment Used

- **Power Supply**:
  - DC Power Supply  
  - Analog & Digital Training System (**M21-7000A**)

- **Measurement Tools**:
  - Oscilloscope: **HAMEG HM203-5 / HM303-6**
  - Digital Multimeter Bench: **MCP MT8045**

- **Components**:
  - Breadboard  
  - Silicon diodes  
  - **4.7 kΩ resistors**

---

## Key Findings

### Theoretical vs. Experimental Results
For a simple resistive rectification circuit with an **8 V<sub>p-p</sub>** input signal:
- **Maximum output voltage (V<sub>max</sub>)** ≈ **3.4 V**
- **Average output voltage (V<sub>μ</sub>)** ≈ **1.3 V**

These results closely match theoretical expectations when diode voltage drops are considered.

---

### Waveform Observation
- During the **positive half-cycle**, the diode is forward-biased, allowing current flow and producing a sinusoidal output.
- During the **negative half-cycle**, the diode is reverse-biased, resulting in **zero output voltage**.

This confirms correct half-wave rectification behavior.

---

# Installation & Setup Guide  
**Rectification Circuits — Electronics (UNIWA)**

This guide describes how to install, set up, and use the **Rectification** laboratory project.  
The repository contains **assignment instructions**, **theoretical analysis**, **Multisim simulations**, **graphs**, and **experimental lab results** related to **half-wave** and **full-wave (bridge) rectification**.

Repository:  
https://github.com/Electronics-aka-Uniwa/Rectification.git

---

## Prerequisites

Before using this project, ensure the following requirements are met.

---

### 1. Software Requirements

#### NI Multisim
- **NI Multisim 14 or newer**
- Required for:
  - Opening and running rectifier circuit simulations
  - Observing rectified waveforms
  - Measuring peak, average, and ripple voltages

Used in folders:
- `lab1b/`
- `lab2a/`
- `lab2b/`
- `lab3b/`

---

#### PDF Reader
- Any modern PDF reader (Adobe Reader, browser-based viewer, etc.)
- Required to open:
  - Assignment instructions
  - Theoretical documentation (English & Greek)

---

#### Image Viewer
- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Waveform graphs
  - Multisim screenshots (`.png` files)

---

### 2. Hardware Requirements (Optional – Physical Lab)

Required **only if** you intend to reproduce the experiments physically in a laboratory.

- **Analog & Digital Training System:** M21-7000A  
- **DC Power Supply**
- **Oscilloscope:** HAMEG HM203-5 or HM303-6  
- **Digital Multimeter:** MCP MT8045  
- **Electronic Components**
  - Silicon diodes  
  - Resistors: **4.7 kΩ**  
  - Breadboard  

> Hardware is **not required** for theoretical study or Multisim simulations.

---

## Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Rectification.git
cd Rectification
```

### 2. Read Theoretical Documentation
Open the files in the `docs/` directory:
- English: `Rectification.pdf`
- Greek: `Ανόρθωση.pdf`

These documents cover:
- Half-wave rectification
- Full-wave (bridge) rectification
- Diode conduction and cutoff
- Voltage drop and efficiency considerations

### 3. Review Assignment Instructions
Navigate to the `assign/` folder and open:
- English: `Exercise-5th-Rectification.pdf`
- Greek: Άσκηση-5η-Ανόρθωση.pdf

These files define:
- Required circuits
- Measurement procedures
- Analysis questions and expected results

### 4. Run Multisim Simulations
#### Simple Rectification
1. Open NI Multisim.
2. Navigate to:
```bash
lab1b/
```
3. Open the provided Multisim file.
4. Run the simulation.
5. Observe:
    - Half-wave rectified output
    - Diode conduction during positive half-cycles

#### Diode-Switch Experiments
1. Open Multisim.
2. Navigate to:
```bash
lab2a/   (diode conducts)
lab2b/   (diode does not conduct)
```
3. Open and run the circuit files.
4. Observe:
    - Conduction and cutoff regions
    - Output waveform differences

### Bridge (Full-Wave) Rectification
1. Open Multisim.
2. Navigate to:
```bash
lab3b/
```
3. Open the bridge rectifier project files.
4. Run the simulation.
5. Observe:
    - Full-wave rectified output
    - Improved output stability compared to half-wave rectification

---

## View Experimental Results
- Graphs & Measurements
  - Found in `lab2a/`, `lab2b/`, and `lab3b/`
- Multisim Screenshots
  - Included in the corresponding lab folders
- Laboratory Photos
  - `photos-in-lab/`

These materials document the comparison between:
- Theoretical calculations
- Simulation results
- Experimental measurements