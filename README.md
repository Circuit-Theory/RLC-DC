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
  <strong>Circuit Theory</strong>
</p>

<h1 align="center" style="letter-spacing: 1px;">
  RLC Components, Transient Response
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
  <strong>Nikolaos Katsos</strong><br>
  Student ID: 21390084
</p>


<p align="center">
  Supervisor: Christos Kampouris, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://www.syros.aegean.gr/en/staff/research-staff/phd-candidates/christos-kampouris" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Co-supervisor: Georgios Antoniou, Laboratory Teaching Staff
</p>
<p align="center">
  <a href="https://ice.uniwa.gr/en/emd_person/georgios-antoniou/" target="_blank">UNIWA Profile</a>
</p>

<p align="center">
  Athens, May 2022
</p>

---

## Project Overview

This project, titled **"RLC Components, Transient Response"** (Project 2), was conducted as part of the **Circuit Theory** course at the **University of West Attica (UNIWA)**, within the **Department of Informatics and Computer Engineering**.  

The primary objective of the project was to analyze and observe the **transient response** of **RC** and **RL** circuits through:

- **Theoretical analysis**
- **Software simulation** using *Multisim*
- **Physical laboratory experimentation**

---

## Table of Contents

| Section | Folder | Description |
|------:|--------|-------------|
| 1 | `assign/` | Assignment material for the Circuit Theory course (DC RLC circuits) |
| 1.1 | `assign/circuit theory rev2021_EXERCISE_2nd.pdf` | Assignment description in English |
| 1.2 | `assign/θεωρία κυκλωμάτων rev2021_ΑΣΚΗΣΗ_2η.pdf` | Assignment description in Greek |
| 2 | `docs/` | Documentation on RLC components transient response (DC analysis) |
| 2.1 | `docs/RLC-Components-Transient-Response.pdf` | English documentation |
| 2.2 | `docs/RLC-Εξαρτήματα-Μεταβατική-Απόκριση.pdf` | Greek documentation |
| 3 | `multisim/` | Multisim simulations for DC RLC circuits |
| 3.1 | `multisim/Q2.ms14` | RLC transient response simulation |
| 3.2 | `multisim/RC.ms14` | RC circuit transient analysis |
| 3.3 | `multisim/RL.ms14` | RL circuit transient analysis |
| 4 | `README.md` | Repository overview and usage instructions |

---

## Project Structure

The report is organized into the following main sections:

- **1.2.1 – RC Component**  
  Analysis of the transient response of an RC circuit, including theoretical derivations, Multisim simulations, and experimental laboratory results.

- **1.2.2 – RL Component**  
  Analysis of the transient response of an RL circuit through theoretical and simulated solutions.

- **1.3 – Questions**  
  Discussion and answers to specific theoretical and practical questions related to the observed circuit behaviors.

---

## Key Components and Equipment

The following equipment and tools were utilized during the laboratory session:

- **Hardware**
  - Breadboard
  - Connection cables
  - Digital multimeter
  - Resistors (various values)
  - Capacitors

- **Power Sources**
  - DC voltage source set to **12 V**
  - Square pulse voltage source at **30 Hz**

- **Software**
  - **Multisim** for circuit simulation

- **Measurement Tools**
  - Oscilloscope (for capturing voltage waveforms)
  - Timer (for recording capacitor charging times)

---

## Key Findings

### RC Transient Response

- When fully charged, a **capacitor behaves as an open circuit**, since the current flowing through it approaches zero.
- The **charging time** is directly proportional to the resistance value.  
  An increase in resistance increases the **time constant**<br>  
   $$\tau = RC$$
   
  resulting in a longer time required for the capacitor to reach full charge.
- A **phase difference** was observed between the input source signal and the capacitor voltage during simulation.

---

### RL Transient Response

- When the current in an RL circuit reaches its maximum value, the **inductor (coil) behaves like a short circuit**.
- The transient response is characterized by an **exponential increase or decrease of current** following a switching event, consistent with theoretical expectations.

---
## Installation Guide

Clone this repository to your local machine. 
```bash
git clone https://github.com/Circuit-Theory/RLC-DC.git
``` 
