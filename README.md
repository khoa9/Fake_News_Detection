# Fake News Detection Using Text Vectorization

This project is a machine learning project that aims to detect fake news articles using text vectorization techniques. It uses a dataset provided by Kaggle, which contains labeled news articles as either "fake" or "real." The goal is to build a classification model that can predict whether a given news article is fake or real based on its text content.

## Dataset

The dataset for this project can be found on Kaggle: [Fake News Dataset](https://www.kaggle.com/c/fake-news/data?select=train.csv). It includes the following files:

- `train.csv`: This file contains the training data with labeled news articles.

## Project Structure

The project is organized as follows:

- **Data Preparation**: We load and preprocess the dataset, including handling missing data, text cleaning, and feature engineering.

- **Text Vectorization**: We use various text vectorization techniques to convert the text data into numerical features that can be used for machine learning. Common techniques include TF-IDF (Term Frequency-Inverse Document Frequency) and word embeddings such as Word2Vec or GloVe.

- **Machine Learning Models**: We build and train machine learning models for text classification. Popular models for text classification include Logistic Regression, Naive Bayes, Support Vector Machines.

- **Model Evaluation**: We evaluate the models' performance using appropriate metrics such as accuracy, precision, recall, F1-score, and ROC AUC.

## How it works

The model processes input news articles through a pipeline that includes text preprocessing, feature extraction, and classification using the SVM model. The output is a prediction on the reliability of the news article.

## Results

This model suite has demonstrated exceptional performance in identifying and filtering fake news content. Key highlights include:

**- Training Set Accuracy**: Achieved 99% accuracy, indicating the model's robustness and its ability to learn from the dataset.
**- Test Set Accuracy**: Maintained high accuracy at 98%, showcasing the model's generalizability and effectiveness on unseen data.
**- Model Selection**: The SVM model was selected as the primary detection tool after extensive testing, outperforming other models in accuracy and reliability.

These results underscore the model's capability to serve as a powerful tool in the fight against misinformation, making it a valuable asset for digital platforms seeking to maintain content integrity.