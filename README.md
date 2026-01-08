# PowerBi_Project
Business Problem:
The airline industry operates with numerous complexities, requiring effective data management and insights into flight schedules,
passenger details, and ticketing systems. This project aims to analyze airline operations for improving efficiency and customer
satisfaction.

Datasets Used:
Flight_Information
Ticket_Information
Passenger_Information
1. Flight Information: Includes FlightID, FlightNumber, Airline, Destination, and Status.
2. Passenger Information: Includes PassengerID, FlightID, and SeatNumber.
3. Ticket Information: Includes TicketID, FlightID, and BookingStatus.

Objective:
To analyze and visualize airline data for operational insights, passenger management, and ticket booking trends using Power BI.

1. Data Preparation and Cleaning
● Extract and transform data in Power Query.
● Cleandata: remove duplicates, handle missing values, and format columns.

2. Data Modeling
● Create relationships between datasets (FlightID as the key).
● Understand cardinality and configure the model appropriately.

4. Enhanced Data Insights
● Addaconditional column to classify flights as "Best" or "To Be Improved" based on status.
● Use"Columnfrom Examples" to extract the flight number from FlightNumber.

6. Calculations Using DAX
○ Total passengers for a specific flight.
○ Total tickets booked.
○ Calculate table of "Best" flights.
  
7. Visualization and Interactive Features
○ Passenger count by airline.
○ Ticket booking statuses.
○ Flights by airline and destination.
● Added interactive features for:
○ Destination and Airline.
○ Quickviews.
○ Airline-specific pages.
   
8. Final Dashboard and Power BI Service
● Design acomprehensive dashboard with key visuals and insights.
● Configure Row-Level Security (RLS) for Airline A data and assign it to a user.

9.Project Insights and Business Impact
•	find reason of high percentage of to be Improved flight that is 59% percentage and try to shift their status to best flight
•	focus on why cancel and pending that is to be improved flight are high in every parameter and overall  
•	focus on rapid improvement in flight condition for Houston and Los angel which is showing really bad flight condition trend
•	implementing airline B strategies in others as airline B is comparatively performing better than other airlines
•	finding a reason for such low percentage of booked ticket (34%) and high percent of not booked tickets
•	why are ticket are getting cancelled and high percent of ticket are pending, finding solution for it to reduce percent of cancel and pending tickets
•	why only Los Angeles showing high percent booking and not other finding reason and gain some positive output from Los Angeles good booking
•	also ensure increase best flight condition for Los Angeles due to its high confirm booking rate

