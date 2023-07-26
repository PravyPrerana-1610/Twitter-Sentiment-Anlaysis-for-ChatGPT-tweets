# Twitter-Sentiment-Anlaysis-for-ChatGPT-tweets
Project Outline:   
Twitter is a platform which brings information from all over the globe in a single click of our phone. It also allows those from diverse backgrounds and demographics to voice their opinion on this information. While a group of people have positive feedback on a particular topic, some people also have negative feedback on the same topic. Sentiment analysis analyzes the sentiment of the tweets and classifies the sentiments that are expressed in the text. It uses natural language processing and machine learning algorithms to classify tweets automatically as positive, negative, or neutral based on their content. This helps in understanding the opinion of people on social media for a variety of topics.
Project Structure:  
1. Data Collection --> Read and load the dataset of tweets with corresponding sentiment labels (positive, negative, neutral).
2. Data Preprocessing --> Preprocessing the tweet text by removing Twitter Handles(@user), special characters, URLs, numbers, punctuation and short words. Tokenizing the text into words or subwords and converting them into numerical representations. Performing stemming to reduce words to their base form(root form).  
3. Data visualization --> Performing data exploration to understand the distribution of sentiment classes and word frequencies. Visualize the distribution of sentiments in the dataset.
4. Text Representation --> Extracting features from cleaned tweets and choosing a text representation technique, here Bag-of-Words and TF-IDF(Term Frequency-Inverse Document Frequency). Converting the preprocessed text data into numerical vectors. 
5. Build the model --> Split the dataset into train and test data. Used machine learning algorithms - Logistic Regression, Naive Bayes Algorithm and Decision Tree Classifier.
6. Model Evaluation --> Training the sentiment analysis model using the training data. Evaluating the performance of the model on the testing data using F1-score.

