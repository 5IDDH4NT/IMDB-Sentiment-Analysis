# Sentiment Analysis on IMDB Movie Reviews  
This repository contains Python code for sentiment analysis on IMDB movie reviews using various machine learning algorithms.

* Table of Contents  
* Introduction  
* Technologies Used  
* Dataset  
* Code Explanation  
* Results

----------------------------------------------------------------------------------------------------------------------------------------------------
_1) Introduction_   
Sentiment analysis is the process of identifying the sentiment expressed in a piece of text. In this project, we perform sentiment analysis on IMDB movie reviews. We use various machine learning algorithms to classify the reviews as positive or negative.  


_2) Technologies Used_  
* Python 3.8  
* pandas 1.3.4  
* NumPy 1.21.4  
* scikit-learn 1.0  
* Matplotlib 3.4.3  
* Seaborn 0.11.2  
* NLTK 3.6.5  
* tqdm 4.62.3  
* wordcloud 1.8.1 



_3) Dataset_  
The dataset used in this project is the IMDB dataset, which contains 50,000 movie reviews. Each review is labeled as either positive or negative.  


_4) Code Explanation_  
The code performs the following tasks:  

* Imports necessary libraries  
* Loads the dataset using pandas  
* Performs data cleaning and preprocessing, including removing punctuation, converting text to lowercase, removing URLs and stop words, and stemming  
* Uses CountVectorizer to convert the preprocessed text data into numerical features  
* Splits the data into training and test sets  
* Trains various machine learning models, including Logistic Regression, Naive Bayes, and Decision Tree  
* Evaluates the models on the test set using accuracy score and confusion matrix  
* Generates a WordCloud visualization of a sample review  



_5) Results_  
The results of each model are displayed in the output. The accuracy of the Logistic Regression model was the highest at 0.8943, followed by Naive Bayes at 0.8432, and Decision Tree at 0.7115. The confusion matrix shows the number of true positives, true negatives, false positives, and false negatives for each model. The WordCloud visualization shows the most common words in a sample review.




-----------------------------------------------------------
