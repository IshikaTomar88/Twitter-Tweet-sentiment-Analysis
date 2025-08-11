<img width="702" height="354" alt="Screenshot (47)" src="https://github.com/user-attachments/assets/2dc384a3-8355-4d42-a82a-c5afa4056523" />

# Problem Statement
The ability to analyze user sentiment through tweets and comments can provide significant value to companies during product launches. By understanding customer behavior and incorporating sentiment analysis, companies can gain insights from user feedback. This empowers them to make informed decisions, take necessary actions, and improve overall revenue by addressing customer concerns and making targeted improvements accordingly.

![Twitter-sentiment-analysis-1](https://github.com/user-attachments/assets/c6bf51c0-d508-4bf6-b3d9-b065a8cf9e4d)

# Machine Learning and Data Science
Our approach involves utilizing machine learning techniques and text extraction to predict the sentiment of a given text, determining whether it is positive or negative. Initially, we will analyze the text and examine the various words present within it. Once we have a comprehensive understanding of the text, we will proceed with the machine learning analysis, employing deep neural networks. The output from this analysis will be utilized in subsequent machine learning operations to generate predictions regarding the sentiment of the text, specifically determining whether it is positive or negative.

# Natural Language Processing (NLP)
We would be using the natural language processing that is required when doing the machine learning analysis. Performing the natural language processing ensures that the words that are present are converted into mathematical vectors that are used for different machine learning models for prediction. Once the mathematical vectors are converted into different vectors, they are given for the machine learning models for prediction respectively. Therefore, with the features that are present in the text along with some newly created features, the machine learning, and deep learning models would be using those techniques and ensures that they are getting the best outputs respectively.

# Vectorizers
It is important to use vectorizers that are important for machine learning. Therefore, a given text which is in the form of a string is converted into a vectorial representation which is what is being used by machine learning models for prediction. Below are some of the vectorizers that were used in the process of converting a text into a mathematical representation.

* Count Vectorizer
* Tfidf Vectorizer

# Machine Learning Models
In this project, there was only one ML model used to get the prediction of the sentiment of tweets. Below is the model that was used for the task of prediction.

* Deep Neural Networks

# Exploratory Data Analysis (EDA)
After performing exploratory data analysis, it could be seen based on the results that there is a comparatively more number of neutral sentences compared to either positive or negative sentiments. With the use of word clouds, it could be seen that words such as good, awesome, and great were used most frequently. On the contrary, it could be seen for the negative word cloud that words such as hate, sorry and sad were used most frequently.

We have an image depicting a dataframe and a list of features. We will utilize the 'text' feature as input and consider the 'sentiment' feature as our target variable. Our goal is to predict the likelihood of a text being categorized as positive, negative, or neutral.

![Input Data](https://github.com/user-attachments/assets/698fb954-fd13-4484-9369-58e356477ba4)

The countplot below illustrates that the majority of texts are classified as neutral sentiment, while the count of negative and positive texts is comparatively lower. This indicates a higher prevalence of neutral sentiments in the dataset.
<img width="742" height="544" alt="Model Performance" src="https://github.com/user-attachments/assets/e559d978-a2fc-40b3-9c9c-5a5d7ada0921" />

Wordcloud gives a good representation by the presence of words based on their size. In other words, more frequent words appear in higher size as compared to others. Words such as "thank" and "day" are used most often in the positive tweets.
<img width="1035" height="550" alt="Positive wordcloud" src="https://github.com/user-attachments/assets/ba1e7bf4-8f0e-4e09-bbae-5e8c4411dfa0" />


The wordcloud provided showcases negative tweets within the dataset. Notably, recurring words like "hate" and "sad" are prevalent, indicating their significance in identifying negative sentiment.
<img width="1038" height="534" alt="Negetive wordcloud" src="https://github.com/user-attachments/assets/5e053649-dbcd-44ad-883d-282176a5bfa0" />

# Hyperparameter Tuning
In our project, after gaining a comprehensive understanding of various machine learning models, we will proceed with hyperparameter tuning. This crucial step aims to select optimal hyperparameters that can yield the best results for each specific model. By carefully selecting these hyperparameters, we can enhance the accuracy and performance of our machine learning models. Our objective is to explore and grasp the influence of different hyperparameters on the models and how they impact the outcomes for various problem statements. Ultimately, we aim to apply these optimized machine learning models in a production environment, leveraging their capabilities to achieve the desired results.

# Results
The observed discrepancy between the training loss and the test loss suggests the presence of overfitting in the data. Despite this, the model could still be utilized for predictions, considering its potential ability to generalize well on unseen test data, despite its exceptionally strong performance on the training data.

![Model Performance](https://github.com/user-attachments/assets/6d06e0a9-ae02-4790-9079-e0d3833048e5)

