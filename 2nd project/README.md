Exploratory data analysis

Visualization of data using histograms and boxes with moustaches. Studying data slices. Finding relationships between different parameters in the data. Join tables.

Getting conclusions from grouped data.

## Tasks

- Calculate and add to the table:
- price per square meter;
  - day of the week, month and year of publication of the ad;
  — floor of the apartment; options-first, last, other;
  - the ratio of the living area to the total area, as well as the ratio of the kitchen area to the total area;
- Explore the parameters: area, price, number of rooms, ceiling height. Plot histograms for each parameter;
- Study the time of the sale of the apartment. Build a histogram. Calculate the average and median. Describe how long it usually takes to sell. When can we assume that sales were very fast, and when is it unusually long?
- Find out what factors most affect the cost of the apartment;
- Study whether the price depends on the square meter, the number of rooms, distance from the center;
- To study the dependence of the price on what floor the apartment is located on: the first, last or other; 
- Also study the dependence on the date of placement: day of the week, month and year;
- Select 10 localities with the highest number of ads, calculate the average price per square meter in these localities. Select the localities with the highest and lowest housing costs;
- Explore apartment offers in terms of distance to the center. Select apartments in St. Petersburg. Find out which area is included in the center;
- Select a segment of apartments in the center. Analyze this territory and find out whether the offers in it differ from the general ones throughout the city.

## Used libraries:
- *pandas*
- *pymystem3*
- *datetime*
- *matplotlib*
- *seaborn*

## Data

The following data from the Yandex service was available for analysis.Real estate-archive of ads for the sale of apartments in St. Petersburg and the nearest settlements for several years:
- Distance to the nearest airport in meters;
- Number of balconies;
- Ceiling height in meters;
- Distance to the city center in meters;
- How many days the ad was placed (from publication to withdrawal);
- Date of publication;
- Floor;
- Total floors in the house;
- Apartments (Boolean type);
- Kitchen area in square meters;
- Price at the time of withdrawal from publication;
- Living area in square meters;
- Name of the locality;
- Free layout (Boolean type);
- Number of parks within a 3 km radius;
- Distance to the nearest park in meters;
- Number of reservoirs within a radius of 3 km;
- Distance to the nearest reservoir in meters;
- Number of rooms;
- Studio apartment (Boolean type)
- The area of the apartment in square meters;
- The number of photos of the apartment in the ad
