# Project 6 : Disaster Tweet Classification

## Problem statement

Twitter has become an important communication channel in times of emergency.
The ubiquitousness of smartphones enables people to announce an emergency they’re observing in real-time. Because of this, more agencies are interested in programatically monitoring Twitter (i.e. disaster relief organization and news agencies).



This Project builds a learning model that classifies Tweets as disaster and no disaster.

## Executive Summary


### Contents

- [Data Collection and Cleaning](#Data-Collection-&-Cleaning)
- [Exploratory Data Analysis](#Exploratory-Data-Analysis)
- [Pre Processing](#Pre-Processing)
- [Modeling](#Modelling)
- [Inferential Visualizations](#Inferential-Visualizations)
- [Conclusions and Recommendation](#Conclusions-and-Recommendation)


### Data Collection & Cleaning


This dataset was created by the company figure-eight and originally shared on their ‘Data For Everyone’ website here.

Tweet source: (https://twitter.com/AnyOtherAnnaK/status/629195955506708480)


### Exploratory Data Analysis
This step involves the following:

>1. Import and Read data - Reading the csv file <br>
>2. Data Visualization - Creating histogram and word cloud <br>
>3. Baseline Accuracy - Calculation <br>





### Pre Processing
This step involves the following methods :

>1. Tokenizing - splitting data into distinct chunks<br>
>2. Removing Stopwords- Removing commonly used words/stop words as they take up space and processing time <br>
>3. Lemmatizing - return the base/dictionary form of a word<br>

### Modeling
 This step creates three models and compares them.

>1. Logistic Regression Model<br>
>2. Naive Bayes Model<br>

Train and Test Scores:

|Model|Train Score|Test Score|
|---|---|---|
|Logistic Regression Model|0.8894727623051323|0.7977941176470589|
|Naive Bayes Model|0.7836748992818356|0.773109243697479


Confusion Matrix Result:

|Model|False Positives|False Negatives|
|---|---|---|
|Logistic Regression Model|0|3|
|Naive Bayes Model|8|0|
|Decision Tree Model|20|15|

### Inferential Visualizations

>1. Creating a desicion tree with Labels <br> 
>2. Creating word clouds for subreddit - Bookclub and Cooking<br>


## Conclusions and Recommendations

 A sucessful model was bult and score was submitted to kaggle.
