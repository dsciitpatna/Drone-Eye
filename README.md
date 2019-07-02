# Drone-Eye
A drone project that performs object detection and make a search engine out of the drone feed.  Project under Machine Learning and AI society of **Developer Students Club - IIT Patna**.

## Motivation
Modern drones are be equipped with cameras and are very prospective for a variety of commercial uses such as aerial photography, surveillance, etc.n. However, there are more challenges with drones due to top-down view angles and real-time constraints. Additionally, a challenging problem is the strong weight and area constraint of embedded hardware that limits the drones to run computation intensive algorithms, such as deep learning, with limited hardware resource.

## Aim
Drone-Eye is a framework that intends to tackle both problems while running on embedded systems that can be mounted onto drones.Deep neural networks, object detection and object searching are the three major components in our work.

![](bloggif.gif)

## Prerequisites
1. Basic Deep Learning concepts.
2. Basics of Convolutional Neural Networks.
3. Object Detection using CNN
4. Tools
* [Pytorch](https://pytorch.org)
* [Tensorflow](https://www.tensorflow.org/)
* [Keras](https://keras.io/)
* Basic python libraries used in ML ([Scikit-learn](https://scikit-learn.org/), [Pandas](https://pandas.pydata.org/), [Matplotlib](https://matplotlib.org/)).

## Hardware Requirements
1. Drone hexacopter or octacopter
  - PixHawk
  - PPM Encoder
  - Propellers
  - 6-8 Brushless Motors
  - 6-8 Electronic Speed Controllers
  - Landing Gear
  - Radio remote
2. [NVIDIA Jetson Nano](https://developer.nvidia.com/embedded/jetson-nano-developer-kit)
3. Camera (USB Cam will do)
4. Gimble

## Pipeline 

### Stage 1

  1. Making/Getting a drone.
  2. Putting on camera.
  3. Computation board like Jetson.

### Stage 2

4. Apply YOLO and other models on the feed of the camera
  - Use object detection with web cam 
  - Find how to do the same task on NVIDIA Jetson Nano
  - Config and Implement the processing on Jetson board with external camera
  - Deploy the setup on the drone
  - Get the relevant info from the drone

### Stage 3

5. Tag the detected objects with GPS location, Compass direction and Time stamp.
6. Send these info on a server.
7. Make a search engine on the detected objects.


## Resources
To be added later on.

## Further Works
Further we may deploy the model and make search engine out of the feed collected from camera.

## Communication
Our chat channel is to be found on Discord [here](https://discordapp.com/channels/544501728498810880/591531461291671563).

## Mentors
* [Sahil Aggarwal](https://github.com/sahilee26) (**Project Lead**)
* [Piyush Chauhan](https://github.com/piyushchauhan)(**Project Mentor**)
* [Sriram Pingali](https://github.com/)
* [Nischal](https://github.com/)



