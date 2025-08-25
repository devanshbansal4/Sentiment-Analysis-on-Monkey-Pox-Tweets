Notebooks for Model Training::

  Bi_LSTM.ipynb – Code for training a BiLSTM model.  
  CNN.ipynb – Code for training a CNN model.
  DistilBert.ipynb – Code for training a DistilBERT model.
  TraditionalModels.ipynb – Code to train Logistic Regression, Naive Bayes, Random Forest, and XGBoost individually. At the end, this notebook also creates an ensemble of these four models for sentiment prediction.
  AdvancedEnsebleHardVoting.ipynb – Ensemble model using hard voting.
  AdvancedEnsebleSoftVoting.ipynb – Ensemble model using soft voting.



Dataset::
  
  MonkeyPoxDataset.csv – Dataset file used for training and evaluation.



Trained Models::

  cnn_model.h5 – Trained CNN model.
  bilstm_atention_model.h5 – Trained BiLSTM model with attention.
  log_reg.pkl – Trained Logistic Regression model.
  nb.pkl – Trained Naive Bayes model.
  xgb.pkl – Trained XGBoost model.
  vectorizer.pkl – Count Vectorizer tokens.
  Note: The trained Random Forest model file (rf.pkl) could not be uploaded because it was too large for Git.



DistilBERT Files
  
  config.json, special_tokens_map, tokenizer_config, vocab – Files required for the DistilBERT model.
  Note: The trained DistilBERT model file (tf_model.h5) could not be uploaded because it was too large for Git.
