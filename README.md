# Twitter-Sentiment-Prediction-of-US-Airlines

**Project Summary:**
Created a Twitter sentiment prediction model for US airlines utilizing supervised machine learning on a Kaggle dataset of tweets expressing positive, negative, and neutral sentiments, while also implementing data cleaning and preprocessing techniques to address various data issues and error patterns.

Applied seven classification supervised machine learning models and analyzed their accuracy, precision, recall, and f-1 score to determine the best model. 

The top 3 models found are Logistic Regression, Support Vector Machine (Classifier) and Neural Network with an accuracy of up to 85%.

Provided valuable insights into customer perceptions of US airlines, allowing airlines to make data-driven decisions to improve their services and better meet customer needs.

**Business Problem Definition:**
Airline companies in the United States face a significant challenge in understanding and managing customer satisfaction. Negative sentiment towards an airline can lead to decreased bookings and revenue. Social media platforms, such as Twitter, provide extensive customer feedback on airline service quality that can be used to gain insights into customer sentiment toward the airlines. However, the sheer volume of data can make it challenging to manually analyze and understand the overall customer sentiment.

**Problem Setting:**
This project aims to predict the sentiment of tweets about US airlines using supervised machine learning techniques. It will understand customer perceptions and predict the sentiment of tweets as positive, negative, or neutral. This model will help airlines make data-driven decisions to identify areas of improvement and tailor their services to meet customer needs better.

**Data Source and Description:**
• Dataset is obtained from Kaggle, and the link is dataset link.
• The original source of this data is Crowdflower's Data for Everyone library.
• The dataset contains tweets expressing positive, negative, and neutral sentiments towards
6 US Airlines. The 6 US airlines are American airline, Delta, US airways, United airline,
Virgin airline, and Southwest airline.
• The data contains tweets from users from the date 16th February 2015 to 24th February 2015
i.e., 9 days of tweets from users. The tweets on a specific day are as follows: 4, 1408, 1344,
1376, 1500, 1557, 3079, 3028 and 1344 for these 9 days.
• The shape of data frame is (14640, 15).
• The dataset contains variables like tweet_id, airline_sentiment,
airline_sentiment_confidence, negativereason, negativereason_confidence, airline, airline_sentiment_gold, name, negativereason_gold, retweet_count, text, tweet_coord, tweet_created tweet_location, user_timezone
     
**Solution Design:**
The proposed solution uses supervised machine learning to predict the sentiment of tweets about US airlines. The solution will consist of the following steps:
1. Cleaning and preprocessing the data for various data issues / error pattern.
2. Present the insights clearly and concisely using data visualization techniques.
3. Training a supervised machine learning model using labeled data on sentiment.
4. Using the trained model to predict the sentiment of tweets about US airlines.
5. Continuously evaluate the model's performance and make necessary improvements.
