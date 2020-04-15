# FER Challenge Kaggle

This repository contains the code for [FER Challenge on Kaggle](https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge)

## About Dataset

The data consists of 48x48 pixel grayscale images of faces. The faces have been automatically registered so that the face is more or less centered and occupies about the same amount of space in each image. The task is to categorize each face based on the emotion shown in the facial expression in to one of seven categories (0=Angry, 1=Disgust, 2=Fear, 3=Happy, 4=Sad, 5=Surprise, 6=Neutral).

The training set consists of 28,709 examples. The public test set used for the leaderboard consists of 3,589 examples. The final test set, which was used to determine the winner of the competition, consists of another 3,589 examples.

##  About Model

The model following the trend in VGG16, is built with *19 hidden layers* and *Tensorflow* is used. K-Fold Cross Validation has been also included to prevent overfitting. 

## Training

The model has been trained on kaggle notebooks, utilising the TPUs for minimum runtime.

## Performance

A final accuracies of 95.64 and 92.81 were achieved on the training set and validation set respectively.

## Confusion Matrix:
(Confusion Matrix.PNG)
