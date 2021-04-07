Prefabricated project - 2

Getting data from the database. Preprocessing and overview of the dataset. Formulation of hypotheses taking into account the specifics of the business. Testing hypotheses and preparing conclusions in the format of an analytical report.

## Tasks

- Find the maximum and minimum date. Plot a histogram by date and time;
- Determine at what point the data is complete and discard the older ones;
- Learn what events are in the logs, how often they occur. Sort events by frequency;
- Calculate how many users committed each of these events;
- Sort events by the number of users. Calculate the percentage of users who have ever committed an event;
- Determine the order in which events occur;
- Use the event funnel to calculate the percentage of users who go to the next step of the funnel (from the number of users in the previous step).);
- Determine at which step the most users are lost;
- Determine what percentage of users reaches from the first event to the payment;
- Check whether the statistical criteria find the difference between samples 246 and 247 (A/A);
- Select the most popular event. Calculate the number of users who committed this event in each of the control groups. Calculate the percentage of users who committed this event. Check whether the difference between the groups is statistically significant, the same for the rest of the events;
- Do the same with group B. Compare the results with each of the control groups separately for each event. Compare the results with the combined control group.


## Used libraries:
- *pandas*
- *math*
- *numpy*
- *stats*
- *matplotlib*
- *seaborn*
- *plotly*

## Data

Data was available for analysis:

- event name;
- unique user ID;
- event time;
- experiment number: 246 and 247 are the control groups, and 248 is the experimental group.
