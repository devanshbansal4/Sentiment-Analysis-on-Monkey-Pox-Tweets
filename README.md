Sentiment Analysis Models and Ensembles


This repository contains multiple deep learning and traditional machine learning approaches for sentiment analysis, along with ensemble methods designed for improved prediction performance. All models are trained on the "Monkeypox Dataset.csv" dataset.


## Repository Structure
.
├── Bi_LSTM.ipynb
├── CNN.ipynb
├── DistilBert.ipynb
├── TraditionalModels.ipynb
├── AdvancedEnsembleHardVoting.ipynb
├── AdvancedEnsembleSoftVoting.ipynb
├── Monkeypox Dataset.csv
├── cnn_model.h5
├── bilstm_attention_model.h5
├── log_reg.pkl
├── nb.pkl
├── xgb.pkl
├── vectorizer.pkl
├── config.json
├── tokenizer_config.json
├── special_tokens_map.json
├── vocab.txt
└── README.md


## Notebooks for Model Training ##
## Deep Learning Models
Bi_LSTM.ipynb – Training pipeline for a Bidirectional LSTM model.
CNN.ipynb – Convolutional Neural Network for text classification.
DistilBert.ipynb – Fine-tuning DistilBERT for sentiment prediction.
## Traditional Machine Learning Models
TraditionalModels.ipynb – Trains Logistic Regression, Naive Bayes, Random Forest, and XGBoost models.
Includes an ensemble of all four models for combined predictions.
## Ensemble Approaches
AdvancedEnsembleHardVoting.ipynb – Hard voting ensemble across multiple trained models.
AdvancedEnsembleSoftVoting.ipynb – Soft voting ensemble using probability averaging.


## Dataset
Monkeypox Dataset.csv – Dataset used for training, validation, and evaluation.


## Trained Model Files ##
## Deep Learning
cnn_model.h5 – Trained CNN model.
bilstm_attention_model.h5 – Trained BiLSTM model with attention.
## Traditional ML
log_reg.pkl – Logistic Regression model.
nb.pkl – Naive Bayes model.
xgb.pkl – XGBoost model.
vectorizer.pkl – CountVectorizer for preprocessing text.
Note: Random Forest model (rf.pkl) is excluded due to file size limits.


## DistilBERT Configuration Files ## 
## Required files for tokenization and model setup:
config.json
tokenizer_config.json
special_tokens_map.json
vocab.txt
Note: The trained DistilBERT model weights (tf_model.h5) are not included due to size restrictions.


## Notes
All models can be loaded directly for inference using the provided checkpoints.
Ensemble notebooks demonstrate comparative performance and combined voting strategies.
