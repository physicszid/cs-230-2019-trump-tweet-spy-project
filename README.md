# cs-230-2019-trump-tweet-spy-project
Course project on finding the effect of President Trump's tweets on stock market index

Files:
  - Data_Exploration_4.ipynb: convert and reformat data downloaded from http://www.trumptwitterarchive.com/ and https://wrds-web.wharton.upenn.edu/wrds/ to create training and test data sets.
  - MODEL_baseline.ipynb: baseline model that always predicts no change
  - MODEL_twtext_embedding_LSTM.ipynb: LSTM-based model with word encoding (GloVe)
  - MODEL_embedding_and_price_hist_LSTM.ipynb: LSTM-based model with word encoding (GloVe) and price history input
  - MODEL_USE.ipynb: neural network model using the universal sentence encoder (USE)
 
 
