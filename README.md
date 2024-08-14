# Twitter-Sentiment-Analysis-Detecting-Hate-Speech-in-Tweets-Using-Machine-Learning
## Problem Statement:
The objective of this task is to detect hate speech in tweets. For the sake of simplicity, we say a tweet contains hate speech if it has a racist or sexist sentiment associated with it. So, the task is to classify racist or sexist tweets from other tweets. Formally, given a training sample of tweets and labels, where label '1' denotes the tweet is racist/sexist and label '0' denotes the tweet is not racist/sexist, your objective is to predict the labels on the test dataset.
## Approach:
●	Data Collection: Use the provided dataset of tweets for training and testing. The dataset is split into a 65:35 ratio for training and testing, respectively.
●	Data Preprocessing: Clean the tweet text by removing URLs, special characters, and stop words. Tokenize the text and convert it to a suitable format for modeling.
●	Feature Engineering: Generate features using techniques like TF-IDF, word embeddings.
●	Model Building: Train various classification models such as Logistic Regression, SVM, Random Forest, and deep learning models like LSTM.
●	Model Evaluation: Evaluate the models using metrics such as accuracy, precision, recall, and F1-score. Use cross-validation to ensure robustness.
●	Prediction: Use the best-performing model to predict the labels on the test dataset.
## Results:
The final SVM model achieved an accuracy of 96% on the test dataset.
Precision, Recall, and F1-Score values were 96%, 96%, and 96% respectively, indicating the model's effectiveness in detecting hate speech.



## NOT HATE TWEET
![noHate](https://github.com/user-attachments/assets/7182d3fa-faed-494b-8ba1-8bdf3cb1eae1)

## HATE TWEET
![Hate](https://github.com/user-attachments/assets/7942383e-83ec-4761-9c1f-37188077502e)

