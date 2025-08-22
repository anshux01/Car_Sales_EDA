# Data Dictionary

| Field              | Description                         | Variable Type     | Scale   | Example Value   | Additional Information                          |
|--------------------|-------------------------------------|-------------------|---------|-----------------|-----------------------------------------------|
| Year               | Year of sales                       | continuous         | Interval| 2020            | Calendar year; intervals equal; no true zero   |
| Car_Brand          | Manufacturer brand                  | Categorical      | Nominal | Toyota          | No natural order                               |
| Car_Model          | Specific model name                 | Categorical      | Nominal | Camry           | Model codes/labels                             |
| Car_Type           | Vehicle category                    | Categorical      | Nominal | SUV             | Sedan, SUV, Coupe, etc.                        |
| Price              | Vehicle price in currency           | Continuous       | Ratio   | 5,800,000       | Positive only; zero is meaningful (free)       |
| Units_Sold         | Number of units sold                | continuous         | Ratio   | 430             | Count; zero is meaningful                      |
| Showroom_Location  | City showroom location              | Categorical      | Nominal | Bangalore       | Cities; no natural order                       |
| Customer_Rating    | Average customer rating (1-5 scale) | Continuous       | Interval| 4.5             | Differences meaningful; zero is arbitrary      |
| Fuel_Type          | Fuel type of the vehicle            | Categorical      | Nominal | Petrol          | Petrol, Diesel, Electric, Hybrid               |
