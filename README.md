# An ML Approach for Analyzing Customer Churn provided by a Teleco Company

This is a Capstone Project Submission for DATA SCIENCE CAREER TRACK Certification for Springboard.

The objective of this analysis is to find out a Data Driven business scope to determine what contributes to Customer Churn for a Telecom Company in California in Q2 2022.

The Kaggle dataset can be found [here](https://www.kaggle.com/datasets/shilongzhuang/telecom-customer-churn-by-maven-analytics), data courtesy by [MavenAnalytics](https://www.mavenanalytics.io/) and IBM Cognos.

## CONTEXT:

Customer churn is the percentage of customers that stopped using the company's product or service during a certain time frame.  It costs more to acquire new customers than it does to retain existing customers. This Business Metric helps to understand the reason behind the churn and to take effective initiatives to deal with the churn percentage.

## CRITERIA FOR SUCCESS:

Our goal is to find out what factors may contribute to the Churn of the customers and provide supporting analysis to build an action plan to reduce the Churn.

## SCOPE OF SOLUTION SPACE:

* After the subscription for the service, at which time point the Customers tend to leave most?
* Do the services provided by the company like-Monthly Bills, Internet Speed, Competitor’s Offers contribute to Churn?
* Do Customers' Demography Contribute to churn? (e.g. Location, Family Size, etc)

## CONSTRAINTS WITHIN SOLUTION SPACE:

More than 25% missing entries in the Churn Status and Churn Reason record.

## KEY DATA SOURCES:

Dataset available at kaggle provided by MavenAnalytics.
Dataset sourced from IBM Cognos

## ABOUT THE DATASET:

* The Customer Churn table (7043 rows, 38 columns) contains information on all 7,043 customers from a Telecommunications company in California in Q2 2022.
* Each record represents one customer, and contains details about their demographics, location, tenure, subscription services, status for the quarter (joined, stayed, or churned), and more!

## EXPLORING THE REASONS FOR CHURN:

The exploration of the Churn reason among churned customers revealed some interesting findings. At the end of Q2 2022, 67% of the customers stayed with the service provider and 26.54% of the Customers Churned (a customer churn rate of 25% is considered high).

![](https://github.com/myasmin/Capstone_2_Project/blob/master/image_files/output.png)

The majority of the Churned customers noted the Attitude of the Customer Representative as their reason to churn.

Details on Data Wrangling [here](https://github.com/myasmin/Capstone_2_Project/blob/master/Data%20Wrangling.ipynb).
Details on EDA [here](https://github.com/myasmin/Capstone_2_Project/blob/master/Exploratory%20Data%20Analysis.ipynb).
Details on Data Preprocessing [here](https://github.com/myasmin/Capstone_2_Project/blob/master/PreProcessing%20New.ipynb).
Details on Modelling [here](https://github.com/myasmin/Capstone_2_Project/blob/master/Modelling.ipynb).

Find a project report in [here](https://github.com/myasmin/Capstone_2_Project/blob/master/Customer%20Churn%20Presentation.pdf).

## FINDINGS FROM THE ANALYSIS:

Random Forest and Logistic Regression performed well as clessifiers [details analysis here] (https://github.com/myasmin/Capstone_2_Project/blob/master/Modelling.ipynb), but I felt there is still scope for defining pipelines and finding important features. The ‘Labelbinarizer’ (Scikitlearn library) helped to reduce the dimensionality, but it didn’t comply well for pipeline designing and important feature finding
_________________________________________

