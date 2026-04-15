# Diabetes Dataset Analysis
Principles of Data Science Assignment 2/3 Question 2

## Project Overview
This project explores the Diabetes Dataset and demonstrates data cleaning, random sapling, and bootstrapping. Reports and analysis are also conducted.

## Dataset
The raw dataset contains the following:
- Pregnancies: integer
- Glucose: integer
- BloodPressure: integer
- SkinThickness: integer
- Insulin: integer
- BMI: float
- DiabetesPedigreeFunction: float
- Age: integer
- Outcome: integer binary categorical

## Methods
1. Scanned for zero values in features that should not have zero values. Zero values were loaced in `Glucose`, `BloodPressure`, `SkinThickness`, `Insulin`, and `BMI`. Only few missing values were present for these features so the missing samples were dropped.
2. Random sample obtained from population and observations made regarding `Glucose` and `BMI` feature differnces in the two groups.
3. Bootstrapping performed and bootstrap and population compared using the `BloodPressure` feature.