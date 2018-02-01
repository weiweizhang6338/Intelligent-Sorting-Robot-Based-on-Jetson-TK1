# Intelligent-Sorting-Robot-Based-on-Jetson-TK1
## Brief Introduction
   This is a Student Research Training Program (SRTP) conducted by a group of five undergraduate students from Southeast University(SEU) in China. Our group aims to build an intelligent sorting robot platform with intelligent image processing capabilities.
## Project Background
   In recent years, the combination of computer vision technology and robot has become the trend of image processing and robot development. Such technology makes robots have recognition function similar to human eyes, which makes robots more autonomous and intelligent in practical applications. The sorting technology that applies robots with intelligent image processing capabilities to the production line has broad application prospects.
   
   By deploying the object recognition algorithm at GPU which has powerful processing capability, we can achieve the goals to recognize the objects in real time and operate the manipulator to complete the sorting operation, thus creating an intelligent and automatic sorting robot which can be applied to small-scale and low-workload scenarios.
## Technology Scheme
1. Object Recognition Algorithm------Darknet YOLO

2. Hardware Platform------JetsonRobot AI

3. Manipulator------DOBOT

## Expected Goals
- Train YOLO convolution neural network in order to achieve the identification of target product

- Capture images through the camera within its field of view

- Identify and classify the target object in the image, obtain the position of the target object at the same time(TK1 is responsible for this step)

- Control the DOBOT robot to approach and grab the target object 

- Control the DOBOT robot to move and release the target object to the specified classification area
