# ⚡ Voltage Regulator with Feedback and Overload Protection – Simulation and Analysis

## 📌 Project Overview
This project presents a *linear voltage regulator* with *negative feedback and overload protection, designed and simulated in **OrCAD PSpice. It ensures **stable output voltage* and *prevents damage* due to excessive current draw.

## 🎯 Features
- 🔋 *Voltage stabilization* using a feedback loop.
- 🛡 *Overload protection* via a current-limiting circuit.
- 🌡 *Thermal drift compensation* and stability analysis.
- 📊 *AC/DC sweep simulations* to test circuit behavior.
- ⚙ *Multi-stage amplifier* with a differential pair and Darlington output.

## 📂 Project Structure
📁 Voltage_Regulator_Simulation
├── 📄 schematic.dsn → OrCAD schematic file
├── 📄 simulation.opj → OrCAD simulation project
├── 📄 stability_analysis.dbk → Stability factor evaluation
├── 📄 thermal_drift.png → Graphical analysis of temperature impact
├── 📄 overload_protection.png → Overcurrent limiting mechanism
├── 📄 README.md → Project documentation

markdown
Copiază
Editează

## 🛠 Requirements
- *OrCAD PSpice* (for circuit design and simulation)
- *Basic knowledge of power electronics*
- *MATLAB* (optional, for additional analysis)

## 📊 OriginLab Project File

This repository includes a file STAB_TST_19.opj, which is an OriginLab project used for data visualization or analysis related to the database or music metadata.

To open this file:
1. Download [OriginLab](https://www.originlab.com/) (trial version available).
2. Open the file directly in Origin.
3. Explore graphs, statistics, or visual outputs included in the .opj file.

If you do not have Origin, check the /exports folder for static versions (PNG/PDF) of the charts.

## 🚀 How to Run
1. Open simulation.opj in *OrCAD PSpice*.
2. Load the schematic.dsn file to view the circuit.
3. Run *DC Sweep, **AC Sweep, and **Transient Analysis*.
4. Analyze the results from the probe window.
