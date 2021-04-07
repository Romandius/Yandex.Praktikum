# Forecasts and predictions


## Tasks

- Study the average values and standard deviations;
- Look at the average values of the signs in two groups — those who went into the outflow and those who remained;
- Plot bar histograms and feature distributions for those who left (outflow) and those who stayed (did not get into outflow);
- Build a correlation matrix and display it;
- Build a model of binary classification of users, where the target attribute is the fact of user outflow in the next month:
- Split the data into a training and validation sample with the train_test_split function();
- Train the model on a train-sample in two ways-logistic regression and random forest;
- Evaluate the accuracy, precision, and recall metrics for both models on a validation sample. Compare models based on them.
- Perform clustering of objects (users):
- Standardize data;
- Build a distance matrix with the linkage () function on a standardized feature matrix and a dendrogram;
- Train the clustering model based on the K-Means algorithm and predict client clusters (according to the task conditions, the number was 5);
- Build feature distributions for clusters;
- For each received cluster, calculate the share of outflow, select the outflow-prone and reliable clusters.
- Formulate the main conclusions and offer recommendations for the strategy of interaction with users and their retention.

## Used libraries:
- *pandas*
- *math*
- *numpy*
- *stats*
- *matplotlib*
- *seaborn*
- *plotly*
- *sklearn.linear_model*
- *sklearn.ensemble*
- *sklearn.model_selection*
- *warnings*
- *sklearn.metrics*
- *sklearn.preprocessing*
- *scipy.cluster.hierarchy*
- *sklearn.cluster*

## Data

Data was available for analysis:

- the fact of outflow in the current month;
- customer's gender;
- living or working in the area where the fitness center is located;
- an employee of the club's partner company (cooperation with companies whose employees can receive discounts on a subscription — in this case, the fitness center stores information about the client's employer);
- the fact of the initial entry in the framework of the "bring a friend" campaign (I used a promo code from a friend when paying for the first season ticket);
- availability of a contact phone number;
- age;
- time since the first visit to the fitness center (in months);
- duration of the current valid subscription (month, 3 months, 6 months, year);
- the period until the end of the current valid subscription (in months);
- the fact of attending group classes;
- the average frequency of visits per week for the entire time since the start of the subscription;
- average frequency of visits per week for the previous month;
- total revenue from other services of the fitness center: cafes, sports goods, beauty and massage parlors.
