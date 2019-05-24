# USAmin

Project type: School

# Quick Summary
In this group project, we explored if a correlation existed between a movie's summary and its review score.

The dataset was obtained from https://www.kaggle.com/tmdb/tmdb-movie-metadata.

Using the GloVe pretrained word embedding and an LSTM, we obtained a tensor representation of each summary. Then, we passed the tensor into an MLP to obtain a prediction of the review score. Using the review score as a baseline, we performed backpropagation to train our model.

# What I Learned From This Project and Class
- Properly labeled data is very important to the field of deep learning.
- Why a nonlinear activation function is required to properly train a model.
- How LSTM's work around the exploding and vanishing gradient problem present in RNN's.
- Tuning parameters requires patience and a lot of time.
