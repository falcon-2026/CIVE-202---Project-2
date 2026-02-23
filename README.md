# CIVE-202---Project-2
---
## Project Description

NDOT has engaged our firm to transition its current concrete mix design process from Excel to a Python-based system. The goal of this project is to automate the logic contained in the “Mix Design” worksheet so that users can enter material properties and design parameters through a clear step-by-step workflow. The objectives of this project include translating Excel logic into Python, implementing user inputs step-by-step, generating a final mix design output, and researching and preparing four concrete mix scenarios.

---
## Repository Structure

- [Raw_data](mix-design-submittal.xlsx)
- [Notebook(Project_2_Code)](Project2_Code.ipynb)

---
## User Guide

### 1. Program Overview
The system will produce an automatically generated weight chart for one cubic yard of concrete.

**Exmaple:**
This program performs a concrete mix design calculation using the NDOT Mix Design submittal template formulas. It determines required cement materials amount, water-cement ratio, aggregates, fly ash, silica fume, and water content based on user-defined strength and material properties.

### 2. Units
- All units must be in pounds per cubic yard.

### 3. Methods
- All coding was done in a jupyter notebook and all methods were executed by Python functions and coding.
- Create functions to calculate water weight, cement volume, fly ash volume, silica volume, other SCM volume, air volume, water volume, total aggregate volume, coarse aggregate volume, and other aggregate volume. Parameters are defined based on required mathematical components.
- After each funtion is defined, use the string of user inputs and provide the code with values to be used in the calculations. Input the project number and concrete class, along with the following prompted inputs.

`Using Scenario 1's values, here is the weight chart produced from our code.`
