# Question Answer Classification using NLP

This project focuses on classifying question-answer text data using Natural Language Processing (NLP) and machine learning/deep learning models. The dataset contains question-answer samples that are processed, analyzed, and used to train classification models.

## Project Overview

The main goal of this project is to build a text classification system that can automatically classify question-answer data into appropriate categories. The project includes data loading, exploratory data analysis, text preprocessing, feature extraction, model training, and model evaluation.

## Dataset

The project uses the following datasets:

- `Question Answer Classification Dataset 7.csv` — training dataset
- `[Updated] Question Answer Classification Dataset[Test].csv` — testing dataset

## Features of the Project

- Data loading and inspection
- Exploratory Data Analysis
- Text preprocessing
- TF-IDF feature extraction
- Word2Vec Skip-gram embedding
- Deep learning model implementation
- Model evaluation using accuracy, F1-score, classification report, and confusion matrix

## Models Used

The notebook includes different NLP classification approaches, such as:

- TF-IDF based machine learning models such as naive bayes, logistic regression and random forest
- Simple RNN
- Bidirectional RNN
- LSTM
- Bidirectional LSTM
- GRU

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- TensorFlow / Keras
- Gensim
- Jupyter Notebook

## Project Structure

```text
question-answer-classification-nlp/
│
├── QA_classifier.ipynb
├── Question Answer Classification Dataset 7.csv
├── [Updated] Question Answer Classification Dataset[Test].csv
└── README.md
