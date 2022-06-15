# Sentiment Analysis
The purpose of this project is to analyze the impact of the COVID-19 pandemic on people’s mental health through material published in the New Straits Times. It is due to the mental health of the people will have an impact on the policies and procedures of the society and government. For instance, the lockdown introduced to control the COVID-19 has caused some people to have suicidal tendencies by staying at home for long periods of time. The second purpose of this study is to analyze and observe the trends of COVID-19 through changes in people’s emotions. For example, people will have more positive emotions when the epidemic is reduced.

# Background of the applications
Sentiment analysis is a methodology for analyzing a piece of text to discover the sentiment hidden within it. It is the use of natural language processing (NLP), machine learning, and other data analysis techniques to analyze and derive objective quantitative results from raw text. Moreover, sentiment analysis allows us to examine the feelings expressed in a piece of text. It is the automated process of analyzing text to determine the sentiment expressed as either positive or negative. Some popular sentiment analysis applications include social media monitoring, customer support management, and analyzing customer feedback.

In the background of sentiment analysis, advanced AI algorithms apply language deconstruction techniques, like tokenization, part-of-speech tagging, parsing, and lemmatization to break down and make sense of text. After performing text processing,  the feature selection and extraction techniques which play a key role in determining the accuracy of the model are chosen for extracting the features. 

After that, sentiment analysis is performed by determining the polarity of the sentiment. The goal of polarity detection is to decide whether a text expresses positive or negative sentiment. After performing sentiment analysis, machine learning algorithms are used to classify the text based on sentiment. Various machine learning algorithms are applied to classify the sentiment such as naive bayes (NB), k-nearest neighbour (KNN), support vector machine (SVM),  random forest, logistic regression, decision tree and xgboost. Finally, validation and evaluation of the obtained results is performed to determine if the algorithms are able to classify the sentiment accurately. 

# Proposed test plan/hypothesis
Test Plan 1
The first test plan is to build a crawler that is able to crawl the data. We decided to crawl the data about the "Covid-19" articles from the New Strait Times website. The dataset will be used for sentiment analysis purposes.

Test Plan 2
The second test plan is to use multiple machine learning algorithms to train the dataset. The accuracy of each model will be compared to find the best machine learning algorithm and it will be used for testing the user input to check if the algorithm is able to classify the sentiment accurately. We decided to do at least six models for testing the accuracy of the machine learning algorithms.

Test Plan 3
The third test plan is using an ensemble learning model to train the dataset. The ensemble learning model is to combine all the machine learning algorithms that were used in the test plan 2 to train the data and classify the sentiment.
