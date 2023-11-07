# SMS-spam-classification-using-NLP
This repository presents a comprehensive analysis of SMS spam classification using Natural Language Processing (NLP) techniques and various machine learning models. The project aims to distinguish between spam and non-spam SMS messages, providing valuable insights into text classification.

Steps
1. Importing Libraries
In this initial step, essential Python libraries, including NLP libraries such as NLTK and scikit-learn, are imported. These libraries facilitate data preprocessing and model building.

2. Dataset Loading
The SMS dataset containing labeled spam and non-spam messages is loaded. This dataset serves as the foundation for training and testing the machine learning models.

3. NLP Preprocessing
NLP techniques are applied to the SMS messages, including:

Tokenization: Breaking down text into individual words or tokens.
Stemming: Reducing words to their root or base form to improve text normalization.
Stopword Removal: Eliminating common and uninformative words to reduce noise in the data.
TF-IDF Vectorization: Converting text data into numerical features for machine learning models.

4. Machine Learning Models
Multiple machine learning models are employed for SMS classification, including:

Support Vector Classifier (SVC)
Multinomial Naive Bayes (MultinomialNB)
Random Forest Classifier
AdaBoost Classifier
These models are trained on the preprocessed SMS data to classify messages as spam or non-spam.

5. Performance Evaluation
The performance of each machine learning model is evaluated using common classification metrics, such as accuracy, precision, recall, F1-score, and ROC curves. This step helps identify the most effective model in accurately classifying SMS messages.

The results obtained from this project can be invaluable for identifying and filtering spam messages in real-world applications, enhancing communication security, and reducing unwanted SMS clutter.




