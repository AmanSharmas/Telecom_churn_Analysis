# Capstone project EDA (Telecom churn analysis)

Exploratory Data Analysis (EDA) refers to the critical process of performing initial investigations on data so as to discover patterns,to spot anomalies,to test hypothesis and to check assumptions with the help of summary statistics and graphical representations.

## Tableau Dashboard Link: https://public.tableau.com/views/TelecomchurnAnalysis/TelecomChurnDashboard?:language=en-US&:display_count=n&:origin=viz_share_link

### EDA process involves:
Understanding the variables and the structure of the dataset is the initial stage in this process.
Data preprocessing and cleansing are critical components of EDA.
Identifying errors, detect outliers or anomalous events.
Examine the relationships among the variables.
Apart from the above, there is also the ‘Classification or Clustering analysis’ technique used in EDA. 
It is an unsupervised type of machine learning used for the classification of input data into specified 
categories or clusters exhibiting similar characteristics in various groups. 
This can be further used to draw important interpretations in EDA.

### Libraries used in Eda:
1. Pandas
2. Numpy
3. Matplotib
4. Seaborn
5. Plotly

### Graphs used for representation:
1. Bar plot
2. Pie plot
3. Box Plot
4. Grouped bar plot
5. Doughnut plot
6. Venn diagram
7. Heatmap
8. Pair plot
9. Scatter plot

The telecom market in the US is saturated and customer growth rates are low.
They key focus of market players therefore is on retention and churn control. 
This project explores the dataset to identify the key drivers of churn and grab key insights from the dataset.

### The insights gained from the dataset through the use of exploratory data analysis:

The four charge fields are linear functions of the minute fields.
The area code field is anomalous, and can be omitted.
The correlations among the remaining predictor variables are weak, allowing us to retain them all for any data mining model.
Customers making less than 6 International calls tend to churn more frequently.
Long duration callers have faced issues with the quality of service provided which is evident from 
the number of customer service calls made by them i.e. around 3 calls.
Customers with four or more customer service calls churn more often than others.

### Suggestions provided to reduce churn rate in the business:

Reduce the day call charges and can consider providing happy hour kind of offer when there is least call traffic during the day.

Customers opting international plans are quite low (only 9.69%) so there is quite huge market to capture.

Only 28% percent of customers have opted for voice mail plan which can marketed further for increasing revenue.

Provide better customer support & rebate on call tariffs to International callers for better retention as acquiring newer customer 
is 5 times costlier than retaining the old ones.

States where the churn rate is quite high due to more customer service calls, 
In such states West Virginia customer support model can be adopted as the number of services calls were highest but churn has been comparitively quite lower.

Maximum churn percentage is observed in long duration calls & service calls made by long duration callers is upto 3 calls hence improvement in the 
service provided is a essential measure.
