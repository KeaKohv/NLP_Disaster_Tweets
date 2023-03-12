# NLP_Disaster_Tweets
Code for the Kaggle NLP competition for predicting disaster tweets.

The main work is in the notebook "model.ipynb". The data clean-up methods can be found in "clean_data.py".

The best model was a fine-tuned DistilBERT which got an fscore of 0.81 on the Kaggle testset. For comparison, the best real submissions in that Kaggle competition have gotten an fscore around 0.84. There are some submissions which have gotten over that (e.g. fscore of 1) but it has been shown that these submissions are done with leaked testset labels and not predicted by real models.
