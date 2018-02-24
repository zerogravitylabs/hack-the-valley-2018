# Hack The Valley ZGL Challenge 2018
## Prerequisites

We expect challenges with prior knowledge of Python, and machine learning to perform well.
## Challenge

The goal of this challenge is to build a machine learning model to predict future Etherium prices.

The Input data set is already preprocessed and contains training data examples for which to train the model.

Important: We do not allow the integration of outside data.

At the end, the model with the best predictions will win.

For evaluation we use root mean square deviation:
![alt text](rmsd.png)


This repo contains 2 Files:
### train.csv

This file contains the data for training the model.
https://github.com/zerogravitylabs/hack-the-valley-2018/blob/master/train.csv

### predict.csv

This file contains the data points that need to be predicted.
https://github.com/zerogravitylabs/hack-the-valley-2018/blob/master/predict.csv

## Time limit

2 hours
## Submission
For the final submission:

the format of the final prediction is a flat file containing the predicted Etherium price per tick (i.e. data point) per line.

Example

400 . 420 . 300 . 800 . 1100

Please upload both your model and your final predictions.

For helping us processing the submission name the file containing the model:

teamname-model

and the predictions as:

teamname-prediction

Submit both to this dropbox: https://www.dropbox.com/request/h3b72heocloImUtkHiEf
