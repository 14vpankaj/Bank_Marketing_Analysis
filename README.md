URL for Tableau Public Dashboard: https://public.tableau.com/app/profile/pankaj.verma7349/viz/BankMarketingCampaignAnalysis_16428794773550/Story2

# Problem Statement

The data is related to direct marketing campaigns (phone calls) of a Portuguese banking institution. The classification goal is to predict if the client will subscribe to a term deposit.

# Objective

Build ML model to predict if the client will subscribe to a term deposit. Implement exploratory data analysis tools and techniques to investigate, analyze, and summarize the main characteristics of datasets, often utilizing data visualization methodologies.


# What is a Term Deposit?

A Term deposit is a deposit that a bank or a financial institurion offers with a fixed rate (often better than just opening deposit account) in which your money will be returned back at a specific maturity time. For more information with regards to Term Deposits please click on this link from Investopedia: https://www.investopedia.com/terms/t/termdeposit.asp

# Data Description

This is the classic marketing bank dataset uploaded originally in the UCI Machine Learning Repository. The dataset gives you information about a marketing campaign of a financial institution in which you will have to analyze in order to find ways to look for future strategies in order to improve future marketing campaigns for the bank.

Dataset is available on UC Irvine Machine Learning Repository: https://archive.ics.uci.edu/ml/machine-learning-databases/00222/

# Feature

age | int64 | age in years

job | object | type of job (categorical: ['admin.' 'technician' 'services' 'management' 'retired' 'blue-collar' 'unemployed' 'entrepreneur' 'housemaid' 'unknown' 'self-employed' 'student'])

marital | object | marital status (categorical: ['married' 'single' 'divorced'])

education | Object | education background (categorical: ['secondary' 'tertiary' 'primary' 'unknown'])

default | Object | has credit in default? (categorical: ['no' 'yes'])

balance | int64 | Balance of the individual

housing | object | has housing loan? (categorical: ['yes' 'no'])

loan | object | has personal loan? (categorical: ['no' 'yes'])

contact | object | contact communication type (categorical: ['unknown' 'cellular' 'telephone'])

day | int64 | last contact day of the week (categorical: 'mon','tue','wed','thu','fri')

month | object | last contact month of year (categorical: ['may' 'jun' 'jul' 'aug' 'oct' 'nov' 'dec' 'jan' 'feb' 'mar' 'apr' 'sep'])

duration | int64 | last contact duration, in seconds (numeric)

campaign | int64 | number of contacts performed during this campaign and for this client

pdays | int64 | number of days that passed by after the client was last contacted from a previous campaign (numeric; 999 means client was not previously contacted)

previous | int64 | number of contacts performed before this campaign and for this client

poutcome | object | outcome of the previous marketing campaign (categorical: ['unknown' 'other' 'failure' 'success'])

# Label

deposit | object | has the client subscribed a term deposit? (binary: 'yes','no')


# Exploratory Data Analysis

* Find Unwanted Columns
* Find Missing Values
* Find Features with one value
* Explore the Categorical Features
* Find Categorical Feature Distribution
* Relationship between Categorical Features and Label
* Explore the Numerical Features
* Find Discrete Numerical Features
* Relation between Discrete numerical Features and Labels
* Find Continous Numerical Features
* Distribution of Continous Numerical Features
* Relation between Continous numerical Features and Labels
* Find Outliers in numerical features
* Explore the Correlation between numerical features
* Find Pair Plot
* Check the Data set is balanced or not based on target values in classification

# Feature Distribution

![feature_distribution](https://user-images.githubusercontent.com/78812904/163993294-7765db6f-fe45-4983-897a-7f16e13df2b1.png)

# Heat Map

![heatmap](https://user-images.githubusercontent.com/78812904/163993463-4e82b50a-713d-4237-9b97-17eee16bbcbf.png)

# Pairplot

![pairplot](https://user-images.githubusercontent.com/78812904/163993589-fedeaaf7-5829-4670-b57b-ded39f31ab47.png)


![pairplot1](https://user-images.githubusercontent.com/78812904/163993651-ffa14469-e6f6-4832-97ca-bd6ac6943ca1.png)

# Conclusion

- The dataset consists of categorical and numerical features.
- The dateset has 16 independent features, out of these only half of them are important.
- People who are under 36 are more likely to subscribe to the term deposit of the bank.
- People who have some kind of loan, i.e personal or house loan are unlikely to subscribe.
- Education plays an important role, as management, technician, blue-collar and admin professionals are more likely to subscribe.
- Most of the people who subscribed to the term deposit spent more than 10 minutes on the call.
- Married people seemed more interested in term deposits, unlike divorced people.
- During May, July and August, most people subscribed to the term deposit. Hence, the targeted audience should be addressed during the summer.
- Most people made up their minds within the next 3 months since the last campaign.
- The targeted audience should be contacted at least 3 times.

# Team Member

- Pankaj Verma
- Gummala Saiteja
- Alisha D'cunha
