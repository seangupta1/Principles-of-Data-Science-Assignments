# Used Cars Dataset Analysis
Principles of Data Science Assignment 2/3 Question 1

## Project Overview
This project explores the Used Cars Dataset and demonstrates data cleaning, imputation, and encoding. Reports and analysis are also conducted.

## Dataset
The raw dataset contains the following:
- `Name`: string
- `Location`: string categorical
- `Year`: float
- `Kilometers_Driven`: float
- `Fuel_Type`: string categorical
- `Transmission`: string categorical
- `Owner_Type`: string categorical
- `Mileage`: string numerical
- `Engine`: string numerical
- `Power`: string numerical
- `Seats`: float
- `New_Price`: string numerical
- `Price`: float

## Methods
1. Unit standardization
  - `Mileage`
    - String format with number and units
    - Contains both kmpl and km/kg units
    - Converted all to kmpl units
    - Converted datatype to float
  - `Engine`
    - String format with number and units
    - Contains CC units
    - Removed CC and converted datatype to float
  - `Power`
    - String format with number and units
    - Contains bhp units
    - Removed bhp and converted datatype to float
  - `New_Price`
    - String format with number and units
    - Contains Lakh units
    - Removed Lakh units and converted datatype to flaot
    - Many values missing so feature dropped.

2. Imputation was performed on the following features: `Mileage`, `Engine`, `Power`, and `Seats`.

3. One hot encoding performed on the following features: `Fuel_Type` and`Transmission`.

4. New Feature Created
- Tells how efficient the engine is.
- `Mileage_To_Engine_Ratio` = `Mileage` / `Engine`
