# NTU-SC1015-Mini-Project
### About
***
This is our mini project for SC1015 (Team 4 FSCD) - Introduction to Data Science and Artificial Intelligence which focuses on Dataset taken from Kaggle regarding customer comments/reviews for tech companies such as Google, Dell, Apple and Microsoft etc.

### Our Team
***
| Name | Parts Done | Github ID |
| --- | --- | --- |
| Cheng You Jie Eric | Exploratory Data Analysis, Data Pre-processing , Multinomial Naive Bayes Model Approach | @exr32 |
| Chew Wei Hao Kovan | Exploratory Data Analysis, Data Pre-processing , Linear SVC Classifier | @Kovancwh99|
| Joshua Low Shao Zheng | Exploratory Data Analysis, Data Pre-processing , Sequential Neural Network Model| @joshualsz |

### Problem Statement
***
Companies have to spend resources to sort through their customer review to figure out customers’ likes and dislikes. 
Hence, we aim to help companies to streamline the process of determining the experience of their customers by conducting sentiment analysis on customer reviews by focusing on the negative sentiments.

### Predictive Models used
***
1. Multinomial Naive Bayes Model Approach <br>
2. Linear SVC Classifier <br>
3. Sequential Neural Network Model

### Conclusion
***
- The length of text has correlation with the sentiment
- We did different types of analysis in our exploratory analysis but namely, the N-Gram analysis to identify common bi grams associated with each sentiment
- Most commonly pair words: Dell Technologies
- The F1 Score for negative from each models - Multinomial Naive Bayes Model Classifier, Linear SVC classifier and Sequential Neural Network are:  0.78, 0.77 and 0.83 respectively
- Sequential Neural Network had the best results in terms of accuracy with 86% for prediction of true negatives

### What did we learn from this project?
***
- Handling imbalanced datasets using resampling methods and imblearn package
- Multinomial Naive Bayes Model Approach, Linear SVC Classifier and Sequential Neural Network Model
- Logistic Regression from sklearn
- Other packages such as SentimentIntensityAnalyzer, csr_matrix, hstack, XGBClassifier and LabelEncoder
- Collaborating using GitHub
- Concepts about Precision, Recall, and F1 Score
