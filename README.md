# CatVoiceActivator

CatVoiceActivator is a recurrent/LSTM model that can recongnize cats' meowing sound. This project has three parts. A training set generator
synthisizes training samples, a keras training model that trains the recurrent/LSTM model, and a code for testing the trained model.

## Training set generator

This code uses my own cat's recorded meowing sound, some negative sounds and some other background sounds to generate a training set. 

## Training 

A recurrent/LSTM model is built and trained using keras.

## Test

The trained model is evaluated here using some test set. The result is shown below:
![alt text](2020-02-15.png)
