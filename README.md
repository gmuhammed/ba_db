# Querying British Airways Database with POSTGRESQL

**British Airways Database**

This database contains British Airways flights, including prices, distance, departure and arrival cities, and more. It accessible via Bee Keeper URL: postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766.us-east-2.aws.neon.tech/SQL_1_1

| Data Attibute                   | Description |
| --------                        | ------- |
| flight_id (text) (primary key)  | Unique identifier of the flight   |
| actual_flight_date (date)       | Date that the flight departed from its departure location    |
| airline (text)                  | Airline that is responsible for the flight    |
| status (text)                   | 	Status of the flight    |
| departure_city (text)           | City of departure    |
| arrival_city(text)              | City of arrival    |
| total_fuel_consumption (number) | Total consumption measured by liters of petroleum    |
| total_passengers (number)       | Total passengers onboard of the flight    |
| baggage_weight (number)         | Weight of all baggage in kg    |
| bike_bags (number)              | Total number of bikes onboard of the flight    |
| revenue_from_baggage (number)   | Total revenue standardised in £    |
| distance_flown (number)         | Distance between departure and arrival city in km    |

