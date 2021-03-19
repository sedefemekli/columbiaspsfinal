# columbiaspsfinal
This is the completed final assignment for the Introduction to AI with Python course from Columbia Precollege Programs.

## Goal
The main reason I've been taking this course was to learn more about the implementations of machine learning and actively practice using the contemporary technologies
used for data interpretation. On the other hand, I've always wanted to combine CS and music theory in some way, and artificial intelligence seemed like a way to 
make it happen.

This project's aim was to determine the pitch of a single note in the given sound file. With this piece of code, any musical note ranging from A0 to C8 can be 
correctly predicted. Therefore, this code might be used in a future tuner project.

## Dataset
This project uses the NSynth Dataset which contains over 300k sound files with unique single notes formed by different instruments and sources. The dataset consists
of three smaller datasets: train(289,205 files) , valid(12,678 files), test(4,096 files). Due to internet connectivity issues at home, I wasn't able to work with
all three of these datasets. Instead I used the test dataset to train and test the model. The model still works with a small error, but this was achieved by the
model selection.

Link: https://magenta.tensorflow.org/datasets/nsynth

## Algorithm Implemented
I used the Multi Layer Perceptron Algorithm for this code. 

MLPClassifier Documentation: https://scikit-learn.org/stable/modules/generated/sklearn.neural_network.MLPClassifier.html

