📩 SMS Spam Detection Using Machine Learning


**📌 Project Overview**

This project implements an SMS Spam Detection system using Machine Learning techniques.
The objective of the project is to automatically classify SMS messages as spam or ham (not spam) based on their textual content.

The project follows a complete Natural Language Processing (NLP) pipeline, starting from data preprocessing to final model evaluation.

**🎯 Objective**

• To analyze SMS text messages 

• To identify and classify spam messages

• To apply machine learning techniques for text classification

**📂 Dataset Description**

Dataset: SMS Spam Collection Dataset

Source: Kaggle / UCI Machine Learning Repository

Total Messages: ~5,500 SMS messages

**Message Labels:**

• ham → Legitimate (non-spam) message

• spam → Unwanted or promotional message

Only two columns are used:

• Message label (spam / ham)

• Message text

**⚙️ Project Workflow**

**🔹 1. Data Preparation**

The dataset is first loaded and inspected.
Unnecessary columns are removed, and only the message label and message text are retained.
The labels are then converted into numerical form to make them suitable for machine learning models.

**🔹 2. Text Preprocessing**

The SMS text data is cleaned and prepared using NLP techniques:

• Conversion of text to lowercase

• Removal of unnecessary symbols and noise

• Handling of missing or empty messages

This step helps improve the quality of the input data and ensures better model performance.

**🔹 3. Feature Extraction (TF-IDF)**

The cleaned text messages are converted into numerical features using TF-IDF (Term Frequency – Inverse Document Frequency).

TF-IDF helps:

• Assign higher importance to informative words

• Reduce the impact of very common words

• Represent text data in a format understandable by machine learning models

**🔹 4. Model Training**

A Multinomial Naive Bayes classifier is used to train the spam detection model.

Naive Bayes is chosen because:

• It performs well for text classification problems

• It is fast and computationally efficient

• It provides reliable results for spam detection tasks

• The dataset is split into training and testing sets to evaluate the model fairly.

**🔹 5. Model Evaluation**

The trained model is evaluated using unseen test data to measure its performance.

✅ Accuracy Achieved:

**Accuracy: ~97% (approximately)**

The high accuracy indicates that the model is highly effective in distinguishing between spam and legitimate messages.

**📈 Observations**

• Spam messages often contain promotional or suspicious keywords

• TF-IDF effectively captures important words contributing to spam detection

• Naive Bayes performs exceptionally well on this dataset

**🧠 Real-World Applications**

• SMS spam filtering systems

• Email spam detection

• Message moderation platforms

• Fraud and phishing message detection

**🏁 Conclusion**

This project demonstrates how classical machine learning techniques can be effectively used to detect spam messages. By combining text preprocessing, TF-IDF feature extraction, and Naive Bayes classification, the model successfully classifies SMS messages with high accuracy.

