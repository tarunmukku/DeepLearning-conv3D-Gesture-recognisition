Neural Networks Project - Gesture Recognition

Introduction:
 The project is for the development of a deep learning model for the smart-TV that can recognise five different gestures performed by the user which will help users control the TV without using a remote.


Problem statement:
Identify and correctly classify the five gestures from the input data. The gestures are continuously monitored by the webcam mounted on the TV. Each gesture corresponds to a specific command:
•	Thumbs up:  Increase the volume
•	Thumbs down: Decrease the volume
•	Left swipe: 'Jump' backwards 10 seconds
•	Right swipe: 'Jump' forward 10 seconds  
•	Stop: Pause the movie


Problem Definition and Approach:
•	Develop generator method to input a batch of videos to the model. Allocate Weightages to the correct list creation of img_idx, initialization of the batch, correctly looping over the data points in a batch and cropping, resizing and normalisation of the images.
•	Design and train a deep learning model using Conv 3D network / CNN+RNN to get good accuracy with the least possible parameters.

