Prefabricated Project

Preparing data for analysis. Preliminary study of the dataset. Formulation and testing of hypotheses.

Project description

This project is being implemented for the online store "Streamchik", which sells computer games around the world. Historical data on game sales, user and expert ratings, genres, and platforms (such as Xbox or PlayStation) are available from open sources. It is necessary in the course of a research project to determine the patterns that determine the success of the game. Then help you make a choice in favor of whom to bet on a potentially popular product and plan advertising campaigns.

The data is provided until 2016. The first month is December 2016, and the campaign is planned for 2017. We need to work out the principle of working with data.
The data set includes the abbreviation ESRB ( Entertainment Software Rating Board) - an association that determines the age rating of computer games. ESRB evaluates game content and assigns it a suitable age category, for example, "For adults", "For young children" or "For teenagers".


Data description


Name — the name of the game

Platform-platform

Year_of_Release — year of release

Genre-game genre

NA_sales - sales in North America (millions of copies sold)

EU_sales-sales in Europe (millions of copies sold)

JP_sales-sales in Japan (millions of copies sold)

Other_sales — sales in other countries (millions of copies sold)

Critic_Score — critics ' score (maximum 100)

User_Score — user rating (maximum of 10)

Rating-rating from the ESRB organization (English Entertainment Software Rating Board). This association determines the rating of computer games and assigns them a suitable age category.
The data for 2016 may be incomplete.


## Tasks

- Study the sales of games by number in different years;
- Learn how sales have changed across platforms;
- Identify the platforms with the highest total sales and build a distribution by year;
- Determine the characteristic lifetime of the platform;
- Based on this period, select the data for the current period, discard the rest;
- Find out which platforms are leading in sales, rising or falling;
- Select multiple potentially profitable platforms;
- Study how user and critic reviews affect sales within one popular platform, build a scatterplot, and calculate the correlation between reviews and sales;
- Correlate the findings with game sales on other platforms;
- Find out if genres with high and low sales stand out;
- Determine the waiting list of users in each region:
- The most popular platforms (top 5), describe the differences in sales shares;
- Most popular genres (top 5), explain the difference;
- Whether the ESRB rating affects sales in a particular region.
- Test hypotheses:
- Average user ratings of the Xbox One and PC platforms are the same;
- Average user ratings of the genres Action (English "action", action games) and Sports (English. "sports competitions») they differ.

## Used libraries:
- *pandas*
- *pymystem3*
- *datetime*
- *matplotlib*
- *seaborn*
- *numpy*
- *stats*
