# Spam Mail Classification
##### This is a project that uses a dataset from Kaggle to create a spam mail classification system. The project is implemented using Python.

## Data Preprocessing
We started by preprocessing the dataset. We used label encoding, word tokenization, stemming, and removed stop words to extract relevant features from the text data. This allowed us to create a dataset of cleaned messages, which we could use for further analysis.

## Vectorization
We then used the Universal Sentence Encoder to convert the cleaned messages into vectors. The Universal Sentence Encoder is a method for converting text data into numerical vectors. We used this to represent each message as a vector, which allowed us to perform similarity calculations.

## Model Selection
We used grid search cross-validation to compare the performance of different machine learning models. We evaluated models like SVM, Random Forest, and Naive Bayes to identify the best model for the task.

## Results
After comparing the performance of different models, we found that the SVM model achieved the highest accuracy of 97.85%. This indicates that it is a suitable model for the task of spam mail classification.

## Conclusion
Overall, this project demonstrates the power of using data preprocessing, vectorization, and machine learning models for spam mail classification. By using these techniques, we were able to create a system that accurately classifies spam messages.
