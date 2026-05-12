# Movie Review Sentiment Analysis using NLP and Machine Learning

## Project Overview
This project performs Sentiment Analysis on IMDb movie reviews using Natural Language Processing (NLP) and Machine Learning techniques. The model classifies movie reviews as either Positive or Negative.

The project uses the IMDb dataset along with text preprocessing, feature extraction, and the Multinomial Naive Bayes algorithm for sentiment prediction.

---

## Technologies Used
- Python
- NLTK
- Scikit-learn
- Pandas
- NumPy
- Hugging Face Datasets

---

## Features
- Text preprocessing using NLP
- Stopword removal and stemming
- Feature extraction using CountVectorizer
- Sentiment classification using Naive Bayes
- Real-time user review prediction
- Model evaluation using accuracy score and classification report

---

## Machine Learning Concepts Used
- Natural Language Processing (NLP)
- Text Cleaning
- Tokenization
- Stopword Removal
- Stemming
- Bag of Words
- CountVectorizer
- Naive Bayes Classification

---

## Dataset
Dataset used: IMDb Movie Reviews Dataset

The dataset contains movie reviews labeled as:
- Positive
- Negative

Dataset Source:  
https://huggingface.co/datasets/imdb

---

## Project Workflow
1. Load IMDb dataset  
2. Convert labels into positive/negative sentiment  
3. Clean and preprocess text  
4. Remove stopwords and apply stemming  
5. Convert text into numerical vectors using CountVectorizer  
6. Split data into training and testing sets  
7. Train Multinomial Naive Bayes model  
8. Evaluate model performance  
9. Predict sentiment for user input reviews  

---

## Model Evaluation
The model performance is evaluated using:
- Accuracy Score
- Classification Report

---

## How to Run the Project

### Install Required Libraries
```bash
pip install pandas numpy nltk scikit-learn datasets
```

### Run the Project
```bash
jupyter notebook
```

Open:
`Sentiment_analyzer_project.ipynb`


---
## Output
```text
Enter your review: This movie was amazing and inspiring!

Sentiment: Positive 😊
```
```text
Enter your review: Worst movie I have ever watched.

Sentiment: Negative 😞
```
