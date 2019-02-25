# DriveSafe
This repo has keras CNN model
According to the CDC motor vehicle safety division, one in five car accidents is caused by a distracted driver. Sadly, this translates to 425,000 people injured and 3,000 people killed by distracted driving every year.

This project hopes to improve these alarming statistics, and better insure their customers, by testing whether dashboard cameras can automatically detect drivers engaging in distracted behaviors. Given a dataset of 2D dashboard camera images, we classify each driver's behavior. Are they driving attentively, wearing their seatbelt, or taking a selfie with their friends in the backseat?

# Libraries Used
os, OpenCV, pandas, numpy, matplotlib, scipy, Keras, PIL

# Dataset Used
State farm distracted driver dataset from kaggle

# Training
We have 10 classes categorising the activities drivers are indulged into.For each class we are given a separate folder to train the model.

# Testing 
We will be given an image taken from  the dashboard of the car. We have to predict a vector of probabilities of 10 classes which would describe what driver is doing and eventually tell if he is distracted or not.
