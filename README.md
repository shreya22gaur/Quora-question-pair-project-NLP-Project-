# Quora Question Pair Similarity Detection

## Overview

This project is a Natural Language Processing (NLP) application that identifies whether two questions from Quora have the same meaning. The goal is to detect duplicate questions and improve the efficiency of question-answer platforms by reducing redundant content.

## Problem Statement

Users often ask similar questions using different wording. This project predicts whether a pair of questions are duplicates by analyzing their semantic similarity using NLP and Machine Learning techniques.

## Features

* Text preprocessing and cleaning
* Tokenization and stop-word removal
* Feature engineering for question similarity
* Duplicate question prediction
* Machine Learning-based classification
* Interactive prediction interface

## Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib
* Seaborn
* Streamlit (for deployment)

## Dataset

The project uses the Quora Question Pairs Dataset, which contains pairs of questions labeled as:

* 1: Duplicate Questions
* 0: Non-Duplicate Questions

## Workflow

1. Data Collection
2. Data Cleaning and Preprocessing
3. Exploratory Data Analysis (EDA)
4. Feature Extraction
5. Model Training
6. Model Evaluation
7. Deployment

## Machine Learning Techniques

* Text Vectorization (TF-IDF)
* Similarity Features
* Logistic Regression
* Random Forest Classifier
* XGBoost (if used)



## Installation

```bash
git clone <repository-url>
cd Quora-Question-Pair-Detection
pip install -r requirements.txt
```

## Run the Project

```bash
streamlit run app.py
```

## Sample Input

Question 1:

```
How can I learn machine learning?
```

Question 2:

```
What is the best way to study machine learning?
```

Output:

```
Duplicate Questions
```

## Future Enhancements

* Deep Learning Models (LSTM/BERT)
* Semantic Search Integration
* Real-time API Deployment
* Enhanced Feature Engineering

## Conclusion

This project demonstrates the application of Natural Language Processing and Machine Learning techniques to solve a real-world text similarity problem. It helps identify duplicate questions efficiently, improving user experience and content organization on question-answer platforms.
