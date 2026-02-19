<p align="center">
  <img src="https://www.especial.gr/wp-content/uploads/2019/03/panepisthmio-dut-attikhs.png" alt="UNIWA" width="150"/>
</p>

<p align="center">
  <strong>UNIVERSITY OF WEST ATTICA</strong><br>
  SCHOOL OF ENGINEERING<br>
  DEPARTMENT OF COMPUTER ENGINEERING AND INFORMATICS
</p>

<p align="center">
  <a href="https://www.uniwa.gr" target="_blank">University of West Attica</a> ·
  <a href="https://ice.uniwa.gr" target="_blank">Department of Computer Engineering and Informatics</a>
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

<hr>

<p align="center">
  <strong>Supervision</strong>
</p>

<p align="center">
  Supervisor: Panagiotis Giannakopoulos, Professor
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/panagiotis-yannakopoulos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/panos-yannakopoulos-b9b6987/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Supervisor: Ioannis Amorginos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/ioannis-amorginos/" target="_blank">UNIWA Profile</a> ·
  <a href="https://www.linkedin.com/in/%CE%B1%CE%BC%CE%BF%CF%81%CE%B3%CE%AF%CE%BD%CE%BF%CF%82-%CE%B3%CE%B9%CE%AC%CE%BD%CE%BD%CE%B7%CF%82-7185b088/" target="_blank">LinkedIn</a>
</p>

<p align="center">
  Co-supervisor: Eleni Tsalera, Academic Scholar
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/academic_sc_ho/" target="_blank">UNIWA Profile</a> ·
  <a href="https://scholar.google.com/citations?user=-LnaZGgAAAAJ&hl=en" target="_blank">Scholar</a>
</p>

<p align="center">
  Co-supervisor: Michalis Diamantopoulos, Applications Lecturer
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/emd_person/22674/" target="_blank">UNIWA Profile</a>
</p>

</hr>

---

<p align="center">
  Athens, December 2022
</p>

---

<p align="center">
  <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSHEw9GCZnQw7c8Wrh6oUicL6AMNrCw5tdn7g&s" width="250"/>
</p>

---

# INSTALL

## Rectification

This guide describes how to install, set up, and use the **Rectification** laboratory project.  
The repository contains **assignment instructions**, **theoretical analysis**, **Multisim simulations**, **graphs**, and **experimental lab results** related to **half-wave** and **full-wave (bridge) rectification**.

---

## 1. Prerequisites

Before using this project, ensure the following requirements are met.

---

## 2. Software Requirements

### 2.1 NI Multisim

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

### 2.2 PDF Reader

- Any modern PDF reader (Adobe Reader, browser-based viewer, etc.)
- Required to open:
  - Assignment instructions
  - Theoretical documentation (English & Greek)

### 2.3 Image Viewer

- Any standard image viewer
- Required for viewing:
  - Lab photos
  - Waveform graphs
  - Multisim screenshots (`.png` files)

---

## 3. Hardware Requirements

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

## 4. Installation & Setup

### 4.1 Clone the Repository

```bash
git clone https://github.com/Electronics-aka-Uniwa/Rectification.git
cd Rectification
```

### 4.2 Read Theoretical Documentation

Open the files in the `docs/` directory:

- English: `Rectification.pdf`
- Greek: `Ανόρθωση.pdf`

These documents cover:

- Half-wave rectification
- Full-wave (bridge) rectification
- Diode conduction and cutoff
- Voltage drop and efficiency considerations

### 4.3 Review Assignment Instructions

Navigate to the `assign/` folder and open:

- English: `Exercise-5th-Rectification.pdf`
- Greek: Άσκηση-5η-Ανόρθωση.pdf

These files define:

- Required circuits
- Measurement procedures
- Analysis questions and expected results

---

## 5. Run Multisim Simulations

### 5.1 Simple Rectification

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

### 5.2 Diode-Switch Experiments

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

### 5.3 Bridge (Full-Wave) Rectification

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

## 6. View Experimental Results

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
