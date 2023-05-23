# Twitter_NLP

# About Dataset
This is an entity-level sentiment analysis dataset of twitter. Given a message and an entity, the task is to judge the sentiment of the message about the entity. There are three classes in this dataset: Positive, Negative and Neutral. We regard messages that are not relevant to the entity (i.e. Irrelevant) as Neutral.

# Preprocessing
+ Remove special characters
+ Convert all text to lowercase
+ WordCloud visualizaion
+ Text normalization
+ Tokenization
+ Stemming
+ Removing stopwords
+ Vectorization (using TF-IDF)
+ Train-Test split

# ML Algorithms Used
+ Support Vector Machine Algorithm(SVM)
+ Multinomial NB
+ RandomForestClassifier
+ AdaBoostClassifier
