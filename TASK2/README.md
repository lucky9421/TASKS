Sentiment Analysis with NLP

This project is part of my CODTECH internship tasks.

The objective of this task is to perform sentiment analysis on customer reviews using Natural Language Processing techniques. The model uses TF-IDF vectorization to convert text into numerical features and Logistic Regression for sentiment classification.

Dataset

For demonstration, a small dataset of customer reviews was used. Each review is labeled as either positive or negative sentiment.

Steps Performed

- Created a dataset of customer reviews
- Applied TF-IDF vectorization to convert text into numerical form
- Split the dataset into training and testing sets
- Trained a Logistic Regression model
- Predicted sentiments of test reviews
- Evaluated the model using accuracy and classification report

 Output

The model successfully classifies customer reviews into positive and negative categories. TF-IDF helps in capturing important words in the reviews and Logistic Regression performs the classification.

Observations

- TF-IDF is effective for converting textual data into numerical features.
- Logistic Regression works well for basic sentiment classification tasks.
- Even with a small dataset, the model was able to classify sentiments correctly.

Tools Used

- Python
- Scikit-learn
- Pandas
- Jupyter Notebook
