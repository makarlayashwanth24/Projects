Sentiment Analysis of Financial Market News Using Machine Learning
Sentiment analysis in financial markets involves using machine learning techniques to analyze news articles, social media posts, and other textual data to gauge the sentiment of the market. This can provide valuable insights for investors and traders by highlighting prevailing positive or negative sentiments that might influence market behavior.

1) Text Preprocessing and Feature Extraction:

Convert the raw text data into a numerical format using techniques such as Bag of Words (BoW) or Term Frequency-Inverse Document Frequency (TF-IDF).
The CountVectorizer from "sklearn.feature_extraction.text" is used to convert text data into a matrix of token counts.

2)Data Splitting:

Split the dataset into training and testing sets to evaluate the performance of the model.
This is achieved using 'train_test_split' from 'sklearn.model_selection'.

3)Model Training:

Train a machine learning model using the training data. Common models include Logistic Regression, Naive Bayes, Support Vector Machines, and Random Forests.
The images show the use of 'RandomForestClassifier' from 'sklearn.ensemble'.

4)Model Evaluation:

Evaluate the model using metrics such as accuracy, precision, recall, F1-score, and confusion matrix.
This is done using functions from `sklearn' by importing "confusion_matrix and classification_report".
