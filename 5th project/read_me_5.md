Data collection and storage

The Internet as a source of data for analysis. Data presentation formats. HTTP API technology. The BeautifulSoup library. Introduction to relational databases. Data processing by scripts in the SQL language. Select and Join statements. Database operations: import and export of data. Project. Extract data from the database and give a summary of the operational efficiency of the online store in two cities for the last month.

Project description

You are an analyst of the company " F9 " - a Russian airline that performs domestic passenger air transportation. Hundreds of flights every day. It is important to understand the preferences of users who buy tickets to certain destinations.

You will have to study the database and analyze the demand of passengers for flights to the cities where the largest festivals are held.

Data description

Air transportation database:

Airports table — information about airports:
airport_code — three-letter airport code,
airport_name-airport name,
city — city,
timezone — time zone.
Aircrafts table — information about aircraft:

aircraft_code — aircraft model code,

model-model of the aircraft,

range — flight range.

Tickets table — information about tickets:

ticket_no — unique ticket number,

passenger_id — unique passenger ID,

passenger_name — the passenger's first and last name.




Flights table — flight information:

flight_id — unique flight ID,

departure_airport — departure airport,

departure_time — departure date and time,

arrival_airport-arrival airport,

arrival_time — arrival date and time,

aircraft_code — the unique identifier of the aircraft.

ticket_flights table-the "flights-tickets" butt table»:

ticket_no — ticket number,

flight_id — unique flight ID.




Festivals table — information about festivals:

festival_id — unique festival number,

festival_date — date of the festival,

festival_city — city of the festival,

festival_name — the name of the festival.
