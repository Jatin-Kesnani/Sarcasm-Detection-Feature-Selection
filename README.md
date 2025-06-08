# Sarcasm Detection-Feature Selection

## Project Description
This project focuses on detecting sarcasm in headlines using various NLP techniques and feature selection methods. The implementation involves preprocessing, sentiment analysis, contradiction detection, and machine learning classification.

## Features
- Lemmatization using Stanford CoreNLP
- Sentiment analysis with SenticNet and SentiStrength
- Contradiction detection in sentiment scores
- Coherence checking for multi-sentence headlines
- Feature extraction including emoticons, punctuation, capital letters, slang words, idioms
- Machine learning models using SVM with n-grams and feature space

## Dataset
The project uses the "Sarcasm Headlines Dataset" in JSON format, containing headlines labeled as sarcastic or non-sarcastic.

## Requirements
- Python 3.x
- Required packages:
  - stanfordnlp
  - pandas
  - requests
  - openpyxl
  - Flask
  - senticnet
  - sentistrength
  - spacy
  - nltk
  - scikit-learn

## Usage
1. Run the Jupyter notebook cells in sequence
2. The notebook will:
- Preprocess the data
- Extract features
- Train models
- Evaluate performance

## Results
Evaluation metrics for different approaches are saved in "Evaluation.xlsx" including:
- Contradiction in Sentiment Scores
- N-grams SVC Classification
- Feature-Space SVC Classification
- Combined N-grams & Feature Space

## Files
- `Sarcasm_Headlines_Dataset.json`: Input dataset
- `lemmatizedDataset.xlsx`: Preprocessed data
- `FeatureSet.xlsx`: Extracted features
- `Evaluation.xlsx`: Performance metrics

## Note
The feature extraction process may take significant time (76+ hours for 26,710 tweets).
