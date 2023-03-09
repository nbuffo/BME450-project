# BME450-project

## Title:
“Automated Hand Segmentation of Sodium MRI Imaging of Knee”

## Team members:
Nicholas Buffo (nbuffo)

## Project decription:

This project will use a dataset that has been compiled by me in my research under Dr. Chan of various subjects’ axial slice of high-resolution anatomical reference proton MRI images. These images have 42 axial slices that extend both proximal and distal to the knee. These images will be grayscale and are 256x256 matrices that are output and compiled into an image. The goal is to hand-segment these anatomical reference images to create a mask that can then be applied to the sodium signal that is used to measure the cartilage density. Hand segmentation can take a lot of time and has room for human error and tracing errors. Thus, the goal of this project is to train a neural network that can identify the cartilage in the knee MRI images and create a mask that is used for analysis of sodium concentration. In order to train this, I will hand segment a set of knee MRI images to apply this to a new set of images, and then test this alongside the neural network and compare the mask that is created. 

## ALTERNATIVE PROJECT:

## Title:
“Taxi Fare Prediction in NYC”

## Team members:
Nicholas Buffo (nbuffo)

## Project decription:

An alternative project depending upon time constraints and resources available of the hand segmentation would be to use data produced by the NYC Taxi & Limousine Commission to evaluate parameters to predict the cost of a taxi ride. The NYC Taxi & Limousine Commission produces this data ordered by month and year, along with the pick-up and drop-off dates/times, pick-up and drop-off locations, trip distances, itemized fares, rate types, payment types, and driver-reported passenger counts. The goal would be to create a neural network that would be able to be trained on these parameters that a user could use and plug in their destination, and time of day and the neural network could give an accurate prediction of the fare for this user. 
