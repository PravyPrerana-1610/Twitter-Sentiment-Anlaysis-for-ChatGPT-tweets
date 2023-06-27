# Twitter-Sentiment-Anlaysis-for-ChatGPT-tweets
Twitter is a platform which brings information from all over the globe in a single click of our phone. It also allows those from diverse backgrounds and demographics to voice their opinion on this information. While a group of people have positive feedback on a particular topic, some people also have negative feedback on the same topic. Sentiment analysis analyzes the sentiment of the tweets and classifies the sentiments that are expressed in the text. It uses natural language processing and machine learning algorithms to classify tweets automatically as positive, negative, or neutral based on their content. This helps in understanding the opinion of people on social media for a variety of topics.

In this project, I use machine learning algorithms-Logistic Regression, Naive Bayes and Decision Tree as classifier to analyze the sentiment of the tweets. The performance of these classifier is measured by F1_Score. The aim is to predict the labels on the test dataset. The steps involved in this machine learning problem is:

1.Description of the Data set ---
 (i) Import necessary libraries
 (ii) Read and load the dataset
2.Pre-processing of dataset ---
 (i) Removing Twitter Handles(@user)
 (ii) Removing Punctuation, Numbers, and Special Characters
 (iii) Removing Short Words
 (iv) Tokenization
 (v) Stemming
3.Data Visualization
4.Extract features from cleaned tweets
5.Split Data into Train and Test Data
6.Build the machine learning model ---
 (i) Logistic Regression
 (ii) Naive Bayes Algorithm
 (iii) Decision Tree
7.Model Evaluation & Comparison
