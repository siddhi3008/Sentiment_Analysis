# Sentiment Analysis Project with Multiple Classification Models
Sentiment analysis is a process that involves determining the sentiment or emotional tone expressed in a piece of text. This project focuses on sentiment analysis using multiple classification models, including Support Vector Machine (SVM), KNeighborsClassifier, RandomForestClassifier, DecisionTreeClassifier, and LogisticRegression.

The project workflow includes the following steps:

1. Data Preprocessing: Before applying the models, the data undergoes preprocessing steps. First, threshold values are assigned to classify sentences as positive, negative, or neutral based on their sentiment scores. Additionally, the project involves finding the top negative and top positive sentences in the dataset by analyzing sentiment scores and identifying sentences with the highest negative and positive scores.

2. Dataset Arrangement: The dataset is arranged in descending order based on the compound score, which represents the overall sentiment polarity of a sentence. This allows for identifying the most important sentences in the data based on their compound scores.

3. Vader Sentiment Analysis: The project applies Vader sentiment analysis, utilizing the VADER (Valence Aware Dictionary and sEntiment Reasoner) model. This pre-trained model is designed specifically for sentiment analysis of social media text. It determines the sentiment (positive, negative, or neutral) of a given sentence.

4. Visualization: Visualization techniques are employed to gain insights from the data. One approach is creating a word cloud, which visually represents the most frequently occurring words in the dataframe. This provides a quick understanding of prominent words in the dataset.

Text Normalization: The project includes text normalization, which involves expanding contractions and other word variations into their expanded forms. This ensures consistency and improves the accuracy of sentiment analysis. For example, contractions like "isn't" are expanded to "is not," "I'm" to "I am," and "they're" to "they are."

Lemmatization: Lemmatization reduces words to their base or root form, streamlining the text analysis process. Different word forms are treated as the same word. For example, words like "running," "runs," and "ran" are reduced to their base form, "run."

Model Summary: The models are fitted on the training data, and their performance is evaluated. This evaluation includes predicting sentiment labels on the training data, calculating the accuracy of the predictions, and predicting sentiment labels on the test data. The resulting predictions are used to create a confusion matrix, providing insights into the models' performance.

Analysis of Wrong Predictions: Instances where the models made incorrect predictions are identified and analyzed to understand potential limitations or areas for improvement in the sentiment analysis model.

In summary, this project aimed to develop a sentiment analysis system using multiple classification models and preprocessing techniques. The objective was to accurately classify the sentiment of given text as positive, negative, or neutral. The project involved data preprocessing, model fitting and evaluation, visualization, text normalization, and lemmatization to achieve reliable sentiment analysis results.
