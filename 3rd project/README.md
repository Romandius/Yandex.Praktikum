Statistical data analysis

Study of objects and their relationships using statistical methods. Samples and statistical significance. Detection and processing of anomalies. Project. Analyze the tariffs of the federal mobile operator.

## Tasks

- Calculate and add to the table:
- the number of calls made and minutes spent on the conversation by month;
  - number of messages sent by month;
  - the amount of Internet traffic consumed by month;
  - monthly revenue from each user (subtract the free limit from the total number of calls, messages and Internet traffic; multiply the remainder by the value from the tariff plan; add the subscription fee corresponding to the tariff plan);
- Describe the behavior of the operator's customers based on the sample: how many minutes of conversation, how many messages and how much Internet traffic is required by users of each tariff per month; 
- Calculate the average quantity, variance and standard deviation, build histograms, describe the distributions;
- Test hypotheses:
- the average revenue of users of the "Ultra" and "Smart" tariffs differs;
  - the average revenue of users from Moscow differs from the revenue of users from other regions.

## Used libraries:
- *pandas*
- *pymystem3*
- *datetime*
- *matplotlib*
- *seaborn*
- *numpy*
- *stats*

## Data

Four datasets with the data of the conditional operator "Megaline" were available for analysis:
- Information about users:
  - User name;
  - User's last name;
  - User's age;
  - Date of tariff activation (day, month, year);
  - Date of termination of use of the tariff (if the value is omitted, the tariff was still valid at the time of data upload);
  - The user's city of residence;
  - Name of the tariff plan.
  
- Call information:
- Call date;
  - Call duration in minutes.
  
- Information about messages:
  - Date of the message.
  
- Information about Internet sessions:
  - The amount of Internet traffic spent per session (in megabytes);
  - Date of the Internet session.
  
- Information about the rates:
  - Name of the tariff;
  - Monthly subscription fee in rubles;
  - The number of minutes of conversation per month included in the subscription fee;
  - The number of messages per month included in the subscription fee;
  - The amount of Internet traffic included in the subscription fee (in megabytes);
  - The cost of a minute of conversation in excess of the tariff package (for example, if the tariff includes 100 minutes of conversation per month, then 101 minutes will be charged);
  - The cost of sending a message in excess of the tariff package;
  - The cost of an additional gigabyte of Internet traffic in excess of the tariff package (1 gigabyte = 1024 megabytes).
