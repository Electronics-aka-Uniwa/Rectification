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

# README

## Rectification

The project investigates multiple rectification techniques through:

- **Theoretical analysis**
- **Computer simulation using Multisim**
- **Experimental laboratory validation**

These approaches ensure a complete understanding of rectifier operation and real-world behavior.

---

## Table of Contents

| Section | Folder / File                           | Description                                                                         |
| ------: | --------------------------------------- | ----------------------------------------------------------------------------------- |
|       1 | `assign/`                               | Assignment material                                                                 |
|     1.1 | `assign/Exercise-5th-Rectification.pdf` | Assignment description (English)                                                    |
|     1.2 | `assign/Άσκηση-5η-Ανόρθωση.pdf`         | Assignment description (Greek)                                                      |
|       2 | `componentss/`                          | Lab components and equipment images                                                 |
|       3 | `docs/`                                 | Theoretical documentation                                                           |
|     3.1 | `docs/Rectification.pdf`                | Theory (English)                                                                    |
|     3.2 | `docs/Ανόρθωση.pdf`                     | Theory (Greek)                                                                      |
|       4 | `lab1b/`                                | Lab 1b: Diode conducts experiment images and Multisim file                          |
|       5 | `lab2a/`                                | Lab 2a: Diode conducts analysis images, graphs, and Multisim file                   |
|       6 | `lab2b/`                                | Lab 2b: Diode not conducts experiment images, graphs, and Multisim file             |
|       7 | `lab3b/`                                | Lab 3b: Bridge and double rectification experiments, images, graphs, Multisim files |
|       8 | `photos-in-lab/`                        | Lab photos and equipment in action                                                  |
|       9 | `questions/`                            | Questions related to the lab                                                        |
|      10 | `README.md`                             | Project documentation                                                               |
|      11 | `INSTALL.md`                            | Usage instructions                                                                  |

---

## 1.Core Modules

### 1.1 Simple Rectification with Resistance

- Mathematical analysis of half-wave rectification
- Multisim simulation of the circuit
- Breadboard implementation using:
  - **4.7 kΩ resistor**
  - **Silicon diode**

---

## 2. Simple Rectification with Diode-Switch (Parts A & B)

- Detailed examination of diode-switch behavior
- Analysis of conduction and cutoff states during input signal cycles

---

## 3. Double Rectification with Bridge

- Design and implementation of **full-wave rectification**
- Use of a **diode bridge** to utilize both half-cycles of the input waveform
- Comparison with single rectification in terms of output stability and efficiency

---

## 4. Laboratory Equipment Used

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

## 5. Key Findings

### 5.1 Theoretical vs. Experimental Results

For a simple resistive rectification circuit with an **8 V<sub>p-p</sub>** input signal:

- **Maximum output voltage (V<sub>max</sub>)** ≈ **3.4 V**
- **Average output voltage (V<sub>μ</sub>)** ≈ **1.3 V**

These results closely match theoretical expectations when diode voltage drops are considered.

---

## 6. Waveform Observation

- During the **positive half-cycle**, the diode is forward-biased, allowing current flow and producing a sinusoidal output.
- During the **negative half-cycle**, the diode is reverse-biased, resulting in **zero output voltage**.

This confirms correct half-wave rectification behavior.
