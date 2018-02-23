# Hack The Valley ZGL Challenge 2018

## Prerequisites

We expect challanges with prior knowledge in Python, and machine learning to perrform well.

## Challenge

The goal of this challange is to build a machine learning model to preduct future Etherium prices.

The Input data set is already preprocessed and contains training data examples for which to train the model.


It is important, that we do not allow the integration of outside data.

At the end the model with the best predictions will win.

For evaluation we use root mean square deviation:

![alt text](rmsd.png)

This repo contains 3 Files:


### train.txt
This file contains the data for training the model.


### predict.txt
This file contains the data points that needs to be predicted.

### Time limit
2 hours

## Submission
Whe running model.ipnby it will create an file names output.txt.

For the final submission: 

the format of the final prediction is a flat file containg the predicted Ethrium price per tick (i.e. data point) per line. 

Example

400
420
300
800
1100

Please upload both yout model and your final precitions to this dropbox: https://www.dropbox.com/request/h3b72heocloImUtkHiEf
