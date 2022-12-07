# Restaurant Review Sentiment Analysis Project

## Project Overview
• Created a machine learning model that **detects/classifies a review into a positive or negative review based on the textual data using Natural Language Processing.**<br/>

## How will this project help?
• This project **helps in categorising the reviews into positive or negative.**

## Resources Used
• Packages: **pandas, numpy, sklearn, matplotlib, seaborn, nltk.**<br/>

## Exploratory Data Analysis (EDA)
• Checked that the training data is balanced.


## Data Cleaning
• Removing special character and numbers using regular expression<br/>
• Converting the entire sms into lower case<br/>
• Tokenizing the sms by words<br/>
• Removing the stop words<br/>
• Lemmatizing the words<br/>
• Joining the lemmatized words<br/>
• Building a corpus of messages

## Model Building and Evaluation
**Metric: F1-Score**<br/>
• Random Forest: 0.714<br/>
• **Multinomial Naive Bayes: 0.79**<br/>
![matrix](readme-resources/conf.png)<br/>
_**Note: Evaluation scores are obtained using cross validation.**_

## Predictions
![Prediction](readme-resources/predictions.png)

## Model Deployment
![Prediction](readme-resources/site1.png)
![Prediction](readme-resources/site2.png)
![Prediction](readme-resources/site3.png)
![Prediction](readme-resources/site4.png)


• Web App Link: https://reviewsentimentanalysis0101.herokuapp.com<br/>
