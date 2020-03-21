# Car-Detection-using-Yolo-Algorithm

This project is meant to be used for a self-driving car. As a critical component of this project, I have built a car detection system. To collect data, you've mounted a camera to the hood (meaning the front) of the car, which takes pictures of the road ahead every few seconds while you drive around.
You've gathered all these images into a folder and have labelled them by drawing bounding boxes around every car you found.There are 80 classes that you want the object detector to recognize, so I have represented the class label as cc, either as an integer from 1 to 80, or as an 80-dimensional vector (with 80 numbers) one component of which is 1 and the rest of which are 0.I have used both representations, depending on which is more convenient for a particular step.

In this project , I have  learnt how "You Only Look Once" (YOLO) performs object detection, and then apply it to car detection. Because the YOLO model is very computationally expensive to train, we have used pre-trained weights 


