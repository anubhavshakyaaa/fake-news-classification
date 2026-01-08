# Fake News Classification using Machine Learning

A comparative study of Logistic Regression, Random Forest, and Naïve Bayes for classifying fake vs real news using the Kaggle Fake–Real News dataset. The project uses TF-IDF for feature extraction and GridSearchCV for hyperparameter tuning. Random Forest achieved the best performance with over 99% accuracy on combined title + body text.

## Features
- Text preprocessing (cleaning, lowercasing, stopword removal)
- TF-IDF vectorization
- Model training on title, body, and title+body
- Hyperparameter tuning with GridSearchCV
- Evaluation with accuracy, precision, recall, F1-score
- Error analysis included

## Team Contributions
- **Ayaan:** Data cleaning, preprocessing, training models, results section  
- **Anubhav Shakya:** Error analysis + analysis code, wrote error analysis section  
- **Asif:** Limitations & Ethical Considerations  
- **Naseeruddeen:** EDA, Conclusion & References  

## How to Run
```bash
pip install -r requirements.txt
jupyter notebook
