# Querying British Airways Database with POSTGRESQL

**British Airways Database**

This database contains British Airways flights, including prices, distance, departure and arrival cities, and more. It is accessible via Bee Keeper URL: postgres://Test:bQNxVzJL4g6u@ep-noisy-flower-846766.us-east-2.aws.neon.tech/SQL_1_1

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

<br>

**Questions to Investigate**

<ol>
  <li> [Question Group 1](https://github.com/gmuhammed/ba_db/blob/main/question_group_1/query.sql) </li>
      <ul>
        <li>what are the top 5 flights with the highest revenue</li>
        <li>what is the average fuel consumption per passenger for all flights</li>
        <li>what is the highest average number of bikes onboard per flight</li>
        <li>find flights where the revenue from baggage is significantly higher than the average for all flights</li>
        <li>calculate the total distance flown by each airline</li>
        <li>Identify the top 3 days with the highest total number of arrivals</li>
        <li>Identify the top 3 days with the highest total number of departures</li>
        <li>find flights with maximum and minimum passengers</li>
        <li>find flights with the longest time gap between actual flight date and arrival date</li>
        <li>calculate the average baggage weight for flights with a distance flown greater than 5000 km</li>
        <li>calculate the revenue per kilometer for each flight</li>
        <li>rank airlines based on the percentage of flights that have bike bags onboard</li>
      </ul>
  <br>
  <li>Question Group 2</li>
      <ul>
        <li>Find the top three flights with the highest fuel efficiency relative to the distance flown</li>
        <li>Determine which airlines operate flights between the highest number of unique city pairs</li>
        <li>Examine how the average baggage weight changes across different seasons</li>
        <li>Determine the percentage of total revenue that comes from the carriage of bikes for each flight</li>
        <li>Find the top three cities with the passenger traffic (arriving and departing)</li>
        <li>Analyze how revenue varies based on the duration of the flight (short-haul, medium-haul, long-haul)</li>
        <li>Identify flights that consistently have a high percentage of occupied seats over a specified time period</li>
        <li>Compare the average revenue per kilometer flown for low-cost airlines versus full-service airlines</li>
        <li>Examine how the average baggage weight per flight changes over different time periods (months, quarters)</li>
        <li>Find flights where the revenue from additional services (e.g., bike carriage) contributes significantly to the total revenue</li>
        <li>Determine the percentage of flights that experience delays</li>
        <li>Group flights into distance categories (short-haul, medium-haul, long-haul) and analyze the revenue for each category</li>
        <li>Find flights where the distribution of baggage weights deviates significantly from the average</li>
        <li>Compare the average revenue per kilometer for non-stop flights versus connecting flights</li>
      </ul>

 </ul>
