# Frailty Dataset Analysis
Principles of Data Science Assignment 1 Question 1

## Project Overview
This project explores the Frailty Dataset and computes summeries and qualitative relation of frailty status.

## Dataset
The raw dataset contains the following:
- Height: (inches)
- Weight: (lbs)
- Age: (years)
- Grip strength: (kilograms) measured with dynamometer
- Frailty: (Y/N)

## Methods
- Unit standardization
  - Conversion of Height and Weight to metric units
- Feature engineering
  - Calculating `BMI`
  - Categorizing `Age` to `AgeGroup`
- Encoding
  - Binary encoding `Frailty` to `Frailty_binary`
  - One hot encoding `AgeGroup`
- EDA
  - Computed summary table containing `mean`/`median`/`std` for numeric columns saved to `reports/findings.md`
  - Quantify relation of strength ↔ frailty: computed as correlation between `Grip_kg` and `Frailty_binary` = **-0.47**
