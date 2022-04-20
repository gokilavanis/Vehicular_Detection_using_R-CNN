# A Deep Learning Model of Vehicle Detection System Using R-CNN
The aim of this project is to train the R-CNN model in various car videos and to use the sliding window method to detect different types of vehicles in the output image.

After extracting images from the video we use a crop_data.m file we store the images in a separate folder and label it as

0 in different vehicles.
1 for cars.
2 for two wheels.
3 for Heavy vehicles.
4 for non-motor vehicle items.

The files provided are:
The following model launch files:

train_project.py: Used for data training.
test.py: Upload an image for testing and find cars using the sliding window system.
dataset.txt: a set of images in a formatted sequence.
crop_data.m: matlab code for cropping images from a video.
 
 More than 1098 Images have been extracted from the uploaded video.
