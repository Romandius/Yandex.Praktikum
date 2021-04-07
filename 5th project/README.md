Data collection and storage

The Internet as a source of data for analysis. Data presentation formats. HTTP API technology. The BeautifulSoup library. Introduction to relational databases. Data processing by scripts in the SQL language. Select and Join statements. Database operations: import and export of data. Project. Extract data from the database and give a summary of the operational efficiency of the online store in two cities for the last month.

## Tasks

- Write a parser to collect data from the site about the 10 largest festivals of 2018 (the parsing code is presented in the file request.py);
- Find the number of flights departing in September 2018 on each aircraft model;
- Calculate the number of flights for all models of Boeing and Airbus aircraft in September;
- Calculate the average number of incoming flights per day for each city for August 2018;
- Set the festivals that took place from July 23 to September 30, 2018 in Moscow, and the number of the week in which they took place;
- For each week from July 23 to September 30, 2018, count the number of tickets purchased for flights to Moscow;
- Select the top 10 cities by the number of flights;
- Build graphs: aircraft models and number of flights, cities and number of flights, top 10 cities and number of flights.


## Used libraries:
- *pandas*
- *pymystem3*
- *datetime*
- *matplotlib*
- *seaborn*
- *numpy*
- *stats*

## Data

Data from the air transportation database was available for analysis:

- information about airports:
  - three-letter airport code;
  - name of the airport;
  - city;
  - time zone;
  
- information about aircraft:
  - aircraft model code;
  - aircraft model;
  - number of aircraft;
  
- ticket information:
  - unique ticket number;
  - personal passenger ID;
  - passenger's first and last name;
  
- flight information:
  - unique flight ID;
  - departure airport;
  - departure date and time;
  - arrival airport;
  - arrival date and time;
  - aircraft id;
  
- butt table "flights-tickets":
- ticket number;
  - flight ID;
  
- information about festivals:
  - unique festival number;
  - date of the festival;
  - the city of the festival;
  - name of the festival.


![alt tag](https://pictures.s3.yandex.net/resources/photo_2019-11-08_14-08-31_1573733426.jpg)

