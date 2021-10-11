# Wrangling and Analyse Data- The Tweet Archives of @dog_rates

## Project Overview
In this project, I wrangled, analysed and visualised data from the Twitter user- [@dog_rates](https://twitter.com/dog_rates), also known as **WeRateDogs**. WeRateDogs is a Twitter account that rates people's dogs based on pictures or videos with a humorous comment about the dog.The dogs are rated over 10 although the numerator can be above 10. WeRateDogs has over 4 million followers and has received international media coverage.
The **goal** of this project is to *'wrangle WeRateDogs Twitter data to create interesting and trustworthy analyses and visualizations.'*
**Python**, **Excel** and **Jupyter Notebook** was used for this analysis.

###  Dataset
Three dataset was used for this analysis
1. *twitter-archive-enhanced.csv* - this had tweet id and rating data for each dog from the WeRateDogs Twitter Archive*
2. *image_predictions.tsv* - this contains data about the breed of dogs as classified by a running the twitter archive data through a neural network.
3. additonal data from Twitter - this was gathered programmatically by querying Twitter's API. It includes data about retweets, likes etc, of the tweets from WeRateDogs

### Analysis Approach
This analysis was done systematically by performing the steps described below
1. **Questions:** I reviewed the available data sources and developed analysis questions.
2. **Wrangling:** This steps consist of:
> *Gathering data* from three sources - csv, tsv and Twitter API.<br>
> *Assessing data* visually and programmatically for data quality gaps<br>
> *Cleaning data* to address data quality gaps identified<br>
3. **Storing data** for easy retrieval of the cleaned data. Cleaning was done using the *define, code and test* approach.
4. **Analysing and visualising data** to explore the data, get clarity of the data and get the data story
6. **Reporting:** Two reports were created:
> * Data wrangling efforts and
> * Data analyses and visualizations

### Requirements
* Python
* Pandas
* Numpy
* Matplotlib
* requests
* os
* tweepy
* json
* time
* datetime
* seaborn

## Summary of Findings
* Of the rated dogs, 63.2% are pupper, 24.8% are doggy, 8.1% are puppo while 3.9% are floffer.<br>
* The lowest rated dog is Crystal- a Maltese dog (2) to 14 while the highest rated  dog species is Pembroke, closely followed by the Golden Retriever and French BullDog.<br>
- *Retweets* and *likes* are positively correlated<br>
* 4/5 of the most retweeted were videos of dogs participating in 'fun' activities such as standing on water, blowing bubbles in a bowl of water etc.<br>
* Overall, the unnamed dog in the tweet - 'Here's a doggo realizing you can stand in a pool. 13/10 enlightened af' is clearly the MVP. This can be tied to the fact that the tweet includes a video showing a doggo standing comfortable in water- a feat only the brave undertake!<br>
* If you are aiming for high number of retweets for a dog-related tweet, a video of the dog in a water-related activity is a winner.<br>

## Relevant Links
1. [Data wrangling report](Wrangle and Analyse/WranglingReport.ipynb).
2. [Dog's Hall of Fame](Wrangle and Analyse/DogsHallofFame.pdf)- An Analysis of tweets from @dogrates
3. [Wrangle and Analyse Data](Wrangle and Analyse/WranglingReport.ipynb)in Jupyter Notebook includes code for gathering, assessing, cleaning, analyzing, and visualizing data

*This project was completed to fulfill the requirement for [Data Analyst Nanodegree](https://www.udacity.com/course/data-analyst-nanodegree--nd002) at Udacity.*