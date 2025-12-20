# 🦠 COVID-19 Data Analysis: Reporting Artefacts, Causality, and False Signals

## Executive Summary
This project examines global COVID-19 datasets with a focus on **distinguishing real epidemiological signals from reporting artefacts, structural biases, and false causal assumptions**.

Rather than treating observed spikes and trends as direct reflections of reality, this analysis interrogates:
- how delayed reporting distorts time-series data,
- how geographic boundaries misrepresent transmission dynamics,
- and how commonly cited indicators (hospital beds, smoking prevalence) fail as causal explanations.

The objective is not to produce dashboards, but to **prevent incorrect conclusions from being drawn from superficially plausible visualisations**.

---

## Core Findings (Analyst Notes)

### 1. Apparent Case Spikes Are Reporting Artefacts
A major global spike in confirmed cases aligns with the point at which **China released previously withheld data**, not with a sudden epidemiological acceleration.

**Interpretation:**  
This discontinuity reflects a **reporting lag shock**, not disease dynamics. Treating it as a real spike leads to incorrect policy and modelling conclusions.

---

### 2. Geographic Aggregation Masks System Behaviour
Country-level aggregation assumes political boundaries are meaningful epidemiological units. They are not.

This analysis re-examines regional data using **natural and functional boundaries**, demonstrating that:
- transmission does not respect administrative borders,
- national-level comparisons exaggerate or suppress local effects.

---

### 3. Healthcare Capacity Is Not a Mortality Driver
Contrary to common assumptions, the number of hospital beds does not meaningfully explain mortality differences in this dataset.

**Interpretation:**  
Healthcare capacity appears as a **lagging response variable**, while mortality is driven upstream by:
- population age structure,
- timing of exposure,
- reporting practices.

---

### 4. Smoking Status Does Not Increase Infection Probability
Within this dataset, smoking prevalence does not correlate with higher COVID-19 infection rates.

**Important distinction:**  
This finding concerns **infection likelihood**, not disease severity or outcomes. It highlights the risk of conflating correlated variables with causal mechanisms.

---

## What This Project Is Not
- Not a dashboard exercise  
- Not a generic EDA walkthrough  
- Not a tool demonstration  

The emphasis is on **analytical judgement, causal discipline, and constraint-aware interpretation**.

---

## Project Structure
- `01_Data_Cleaning_and_Prep.ipynb`  
  Cleaning, normalisation, and identification of structural inconsistencies.

- `02_Timeseries_and_Trend_Analysis.ipynb`  
  Time-series analysis with explicit treatment of reporting distortions and false signals.

---

## Tools Used
Python (Pandas, NumPy, Matplotlib, Seaborn)

Tools are incidental. **Reasoning is the deliverable.**

---

## Author
Gazali Ahmad  
Data Analyst with Systems Analysis background  
https://www.linkedin.com/in/gazaliahmad
