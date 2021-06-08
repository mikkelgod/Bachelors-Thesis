# Bachelors-Thesis
This repository contains the bachelors thesis made by Mikkel Godtfredsen in the spring of 2021.

The project consists of the implementation in the form of IPython Notebooks, as implementation was done in Google Colab, as well as a pdf file with the report.

## Abstract
Time series forecasting is an interesting subject in the field of machine learning as it combines the challenges of capturing the structure in long sequences with essentially "predicting" the future. This project explores the transformer, an advanced model architecture implementing the concept of attention, and compares it to the more simple Long Short Term Memory model, a form of gated recurrent neural network that should be able to learn long term dependencies. This project focuses on evaluating and comparing the two models' abilities in making multi-step predictions which is where the challenges in time series prediction are most clear.
The project is concluded with the sentiment that further experimentation of the transformer architecture would be needed to pinpoint the specific contribution of the important elements of the transformer, this includes attention, positional encoding, and masking. However, based on the results of the experimentation and evaluation of the models, it becomes clear that the transformer model performed much better at predicting sequences of time series data than the LSTM model, and attention in the space of time series forecasting is definitely a concept worth exploring further. 
