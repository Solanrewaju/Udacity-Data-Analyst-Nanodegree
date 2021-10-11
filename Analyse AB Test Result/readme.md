# Analyze A/B Test Results for an e-Commerce Website

## Project Overview
In this project, I analysed the data to understand the results of an A/B test run by an e-commerce website. The *conversion* or *conversion rate* was chosen as the metric for this analysis. The **goal** is: *to conduct experiment(s) and analyse data to help the company understand if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.*
**Python** and **Jupyter Notebook** was used for this analysis.

### Requirements
* Python
* Pandas
* Numpy
* random
* Matplotlib
* statsmodels.api

###  Dataset
Two dataset was used for this project.
1. *ab_data* - this contains data about users who visited the e-commerce website
2. *countries* - this contains information on the countries users logged in from

## Summary of Findings
Based on the results of this analysis, the p-value is **not statistically significant** both in the A/B testing and regression. Therefore, there is **no evidence** to suggest that the new page will lead to more conversion than the old-page. Infact, if an individual landed on the new page, they are 1.015 less likely to be converted than than if they landed on the old page, holding all variables constant. This is also supported by result from the probability rate with a difference of -0.001 between the treatment and control group. Furthermore, there was no evidence of that country affects conversion rate.<br>
Overall, I recommend that the e-commerce company **should run the experiment longer before making a final decision**.

## Relevant Links
1. [View report](Analyse AB Test Result/AnalyseABTestResults.ipynb) in Jupyter Notebook.
2. [View report](Analyse AB Test Result/AnalyseABTestResults.html)


*This project was completed to fulfill the requirement for [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) at Udacity.*