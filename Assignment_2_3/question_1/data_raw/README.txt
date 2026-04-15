Dataset: Used Cars

File Format: CSV (UTF-8 encoding)

Columns: 14
Rows: 5847

Columns:
- Name: (string) full car model name and variant
- Location: (string categorical) city where the car is being sold
- Year: (float) manufacturing year of the vehicle
- Kilometers_Driven: (float) total distance driven
- Fuel_Type: (string categorical) type of fuel used (e.g., Petrol, Diesel)
- Transmission: (string categorical) transmission type
- Owner_Type: (string categorical) Number of previous owners
- Mileage: (string numerical) fuel efficiency
- Engine: (string numerical) engine displacement
- Power: (string numerical) engine power
- Seats: (float) number of seats in the vehicle
- New_Price: (string numerical) original price when new
- Price: (float) current selling price

Notes:
- Some features are embeded in strings and may require parsing
- Missing values present in the dataset
- Different units present in each feature so unit conversion may be required
