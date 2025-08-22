# Data Dictionary

| Column             | Description                                     | Data Type | Notes                         |
|--------------------|------------------------------------------------|-----------|-------------------------------|
| Year               | Calendar year of the sale                        | Integer   | Range: 2015 - 2024            |
| Car_Brand          | Vehicle manufacturer brand                       | String    | Examples: BMW, Toyota, Audi   |
| Car_Model          | Specific model name                              | String    | Examples: ModelA, ModelF      |
| Car_Type           | Category of vehicle type                         | String    | Hatchback, SUV, Sedan, Coupe  |
| Price              | Vehicle price in local currency                  | Float     | Contains missing values       |
| Units_Sold         | Number of units sold                             | Float     | Target variable; some missing |
| Showroom_Location  | City where the showroom is located               | String    | E.g., Bangalore, Hyderabad    |
| Customer_Rating    | Average customer rating (1-5 scale)             | Float     | Contains missing values       |
| Fuel_Type          | Fuel category of vehicle                         | String    | Petrol, Diesel, Electric, Hybrid; some missing |
