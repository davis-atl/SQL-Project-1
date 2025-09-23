# MIST4610-SQL-Project1-Group3

## Team Members:
- Lizzie Stewart @lizzie-stewart
- Davis Williams @davis-atl
- Bobby Szramel @RSzramel
- Lauryn Thomas @laurynthomas

## Context:
At QueryQuest, we developed an airline database to model the core operations of a commercial carrier. The system captures details about airlines, flights, passengers, baggage, and in-flight sales. The database allows managers to schedule flights, process passenger bookings, manage baggage records, and track onboard purchases.

While comprehensive in these areas, the model intentionally excludes operational aspects such as pilot and crew assignments, maintenance records, airport logistics, and customer loyalty programs. This focus ensures the database remains streamlined for analyzing flight efficiency, passenger behavior, and revenue performance. 


## Data Model:
This data model, designed by QueryQuest, represents an airline database that supports the storage and management of flights, passengers, baggage, and in-flight purchases.

This model enables the database to support operational airline data such as flight scheduling, passenger bookings, baggage handling, and in-flight sales. It does not extend to other airline functions such as crew assignments, aircraft maintenance, airport logistics, or frequent flyer 

<img width="647" height="550" alt="image" src="https://github.com/user-attachments/assets/808a9e7b-ad2d-4363-b1bb-54420b52fb50" />

## Data Dictionary:
<img width="865" height="403" alt="image" src="https://github.com/user-attachments/assets/0c498193-39fc-446d-a9d6-2053e556284f" />
<img width="861" height="596" alt="image" src="https://github.com/user-attachments/assets/8d83961f-325f-4e4a-bd59-eafd2300f1cd" />
<img width="850" height="393" alt="image" src="https://github.com/user-attachments/assets/00073f6c-1468-42ab-8a3f-436270ba00d8" />
<img width="853" height="440" alt="image" src="https://github.com/user-attachments/assets/3b3fbf0c-f4ad-49d4-bb2a-fc7ccf6f2610" />
<img width="854" height="487" alt="image" src="https://github.com/user-attachments/assets/ab738c80-f0b7-4a5d-86b3-f2f68131fdea" />


## Queries:
1. Query 1 shows the total quantity of snacks sold and the total snack revenue for flights where the flight distance is greater than 900 miles.
<img width="758" height="255" alt="image" src="https://github.com/user-attachments/assets/bb872bc5-301f-46c7-ac2d-23bfc31157bb" />

This query can help managers evaluate snack sales performance specifically on long-distance flights, which can inform decisions about inventory planning and pricing strategies. By understanding how many snacks are sold and the total revenue gained on flights over 900 miles, an airline can better predict demand and optimize product offerings for longer routes.

2. Query 2 shows the average number of passengers on all flights departing from Atlanta airport.
  <img width="752" height="276" alt="image" src="https://github.com/user-attachments/assets/074cc330-7887-4bb6-95de-af00e613973b" />

This query can allow managers to track the average passenger load on flights departing from Atlanta for each airline in the database. This insight can help optimize scheduling and resource allocation by identifying the under- or over-utilized routes, ultimately improving efficiency and profitability.

3. Query 3 shows the total count of first class passengers who checked in baggage on flights during the current month.
  <img width="751" height="247" alt="image" src="https://github.com/user-attachments/assets/276b87d3-0a71-48f2-84d7-4223342781db" />

This query counts how many first-class passengers checked in bags during the current month. This information helps managers understand baggage trends among premium travelers and adjust baggage handling resources or policies accordingly

4. Query 4 shows all airlines and aircraft types operating at this airport with seating capacities below 200 passengers.
  <img width="824" height="430" alt="image" src="https://github.com/user-attachments/assets/0a705776-b35a-4947-a1c2-ad6bac77acc9" />

This query lists all airlines and plane types that have a passenger capacity of fewer than 200 seats. Managers can use this data to identify smaller aircraft, which may be best suited for regional or lower-demand routes.

5. Query 5 shows the list of flights, airplane type and arrival-destination airports from Delta Airlines with a flight distance of more than 4000 miles.
  <img width="636" height="307" alt="image" src="https://github.com/user-attachments/assets/36b40d1f-3408-4e1a-8a1c-a4366d48b8ec" />

This query displays Delta Airlines flights that use specific plane types on routes longer than 4,000 miles, along with their frequency. This allows managers to analyze Delta’s long-haul operations and make informed decisions about scheduling, fleet utilization, and potential route expansion.

6. Query 6 shows the top 5 flights ranked by total profitability, including ticket revenue, baggage fees, and snack sales.
<img width="704" height="308" alt="image" src="https://github.com/user-attachments/assets/affd8d83-5446-46ae-b7c6-e2c7cd1c6313" />

This query identifies the top five flights that generate the highest total revenue, including both ticket sales and in-flight snack purchases. Managers can use this information to analyze which routes are most profitable and prioritize them for future scheduling, marketing efforts, or premium service offerings.

7. Query 7 shows all passengers who are booked on Flight 1, including their relevant details.
  <img width="734" height="313" alt="image" src="https://github.com/user-attachments/assets/007fa9bb-ee7a-457a-aa31-7b659aa3830a" />

This query lists all passengers booked on Flight 1, along with their travel class. This helps managers quickly see the passenger manifest for a specific flight and evaluate seat distribution between classes.

8. Query 8 shows flights where the total checked baggage weight exceeds the average baggage weight across all flights.
  <img width="594" height="365" alt="image" src="https://github.com/user-attachments/assets/2080a198-dd7c-4cb2-83d8-74cdb2c73c1d" />

This query highlights flights with total baggage weight exceeding the system-wide average, allowing managers to spot unusually heavy flights. This insight can be used to better plan fuel requirements, allocate cargo capacity, or identify flights where baggage policies may need adjustment.

9. Query 9 shows all snack items with a unit price higher than $4.
  <img width="449" height="364" alt="image" src="https://github.com/user-attachments/assets/23f4a235-0b76-4804-af81-176c0e002f7f" />

This query retrieves all snacks priced above $4, sorted from most to least expensive. Managers can use this data to review premium-priced items and evaluate whether pricing aligns with passenger demand and overall sales performance.

10. Query 10 shows all passengers booked on flights where the ticket price is above the average ticket price for all flights.
  <img width="658" height="356" alt="image" src="https://github.com/user-attachments/assets/48058e2e-ed14-4839-853d-a9564851c205" />

This query finds passengers traveling on flights with above-average ticket prices, providing insight into who is booking premium routes. Managers can use this to better understand passenger demographics on higher-yield flights and tailor marketing or loyalty programs accordingly.

## Database Information:
<img width="2150" height="692" alt="image" src="https://github.com/user-attachments/assets/b35f2699-5656-4005-960c-416d48755fe3" />

Name of the Database: br_dbw94452

The queries are bookmarked through stored procedures and can be called using the format CALL TP_Qx where "x" is the query number 
