![nyctaxi](https://user-images.githubusercontent.com/71333855/146815346-8096cfaf-a4bb-482f-ba34-f49b33d72aaa.jpeg)

# The Effects of COVID on the New York City Taxi Industry

### Repository Directory

```
├── README.md                           <- The top-level README for reviewers of this project
├── report_notebook.ipynb               <- Narrative documentation of analysis in Jupyter notebook
├── data_cleaning.ipynb                 <- Data pre-processing notebook
└── data_download.ipynb                 <- Notebook for downloading the data
```

### Quick Links
1. [Analysis Notebook](/report_notebook.ipynb/)
2. [Data Pre Processing](/data_cleaning.ipynb/)

# This Project

This project attempts to address the following issues on the effects of the corona virus on travel by taxi in NYC:

1- The economic impact of the pandemic on NYC taxi revenue.

2- What and where the most expensive trip occured as well as the cheapest trip and the difference between these before and during the peak of the pandemic.

3- The most popular payment method and whether it changed as a result of the pandemic.

4- The most expensive day of the week to travel on and whether or not the pandemic affected this.
## Setup

This project's environment is python3.yml

This analysis can be replicated in the following steps:

* 1- Run the data_download notebook [here](/data_download.ipynb/)
* 2- Run the data_cleaning notebook [here](/data_cleaning.ipynb/)
* 3- Run the report notebook [here](/report_notebook.ipynb/)

# The Data
The data was sourced from the NYC.gov website and can be found [here](https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page).

## Concluded Results

### Question 1: How has the coronavirus impacted the NYC taxi industry's revenue?
* The overall amounts paid per trip has dropped significantly during 2019, especially during the month of April due to lack of demand.
* Tip amounts have also generally decreased, especially in the months after March 2020, most likely due to a decrease in income and spending money as result of lockdowns and lay-offs.
* The biggest jump in the passenger count per trip occured during April, during the first quarantine periods and most likely due to social distancing, with the passenger count somewhat declining overall during the pandemic. The majority count was 1 passenger per trip during both 2019 and 2020.
Thus, I've concluded that COVID-19 has negatively impacted the NYC taxi industry's revenue by driving down fares, decreasing the number of trips, and decreasing the amount of tips received.

### Question 2: What were the most and least expensive trips during and before the pandemic?
* The most expensive paid trip in 2019 was on June 18th for 10,650.44 and was between Times Square and Windsor Terrace. The least expensive trip was 2.60 and occured on June 18th between Stuy Town/Peter Cooper Village and Ozone Park.
* The most expensive trip during the pandemic was on December 20, 2020 for a total amount of 8361.36 and was between Westchester Village/Unionport and Co-Op City. The least expensive trip during the pandemic was on November 3, 2020 for 3.80. It occured between the two zones of DUMBO/Vinegar Hill and Dyker Heights.

### Question 3: What was the most popular payment method and has this changed due to COVID-19?
* Credit cards have always been the most popular transaction method, before and during the pandemic.
* The use of cash has significantly decreased since 2019. It is safe to say that COVID-19 has not affected the most popular payment method, but it has most likely decreased the use of cash.

### Question 4: What is the most expensive day of the week to travel and has the coronavirus changed it?
* The most expensive day to travel did change from Thursday to Sunday, most likely due to the pandemic.

* Fares have significantly decreased since pre-pandemic times by an average of $1.85 per trip.
