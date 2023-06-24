# DrowsinessDetection

 For this project we are going to build a CNN that detects whether in an image the eyes are open or closed.
This model is going to be the core of an application that can be used for drowsiness detection.
By placing the phone in front of the driver (with a specific phone holder provided) the app will function as a safety device.
It will be tracking the eye of the driver and in case the eyes close the app will produce a loud sound in order to wake the drive up.
This app can be a very useful safety tool as many of the accidents that happen to driver are related to driving while overly tired.
In the first part of this project we will create and improve the CNN model that detects the images.

We are going to try to improve the model via different ways of optimization, while constantly checking our results also for overfitting. This is accomplished by creating a train-validation-test split where we will keep a part of the data as validation, to recurrently test our model, and an untouched 'test set' that we will use only at the end with our best performing model as 'unseen data'.
