# Conducting a Personal Project for the Robotics Engineering Field
###### By Elijah Stradley

## Table of Contents
* #### [Focus](##Focus)
  * #### [Primary Fields](###Primary-Fields)
  * #### [Computer Vision](###Computer-Vision)
* #### [Tools](##Tools)
  * #### [Hardware](###Hardware)
  * #### [CVM](###CVM)
* #### [Process](##Process)

Personal Projects are a strong tool to improve your portfolio in engineering. Robotics engineering in particular relies on many fields of engineering, and a well-designed project can demonstrate your skill and experience.


## Focus
This project's focus is determined by its relevance and usefulness in the Robotics Engineering job field. The best focus is one that is relevant in the most robotics postions across leading industries.
### Industry Types
According to Market Research reports, the largest valued types of robots are industrial and service robots, making up 75.2% of all industry shares in 2025. 

Though these fields vary in many ways, computer vision is a fundamental part of these shares, with its dependent sales making up almost 4 billion (Fortune Business Insights).
### Computer Vision
Computer vision is one way a robot visualizes its environment. This is commonly done through LiDAR, cameras, and/or radar. 

Once data is collected, the robot uses a computer vision model or CVM. There are a variety of types, including Vision-Language Models (VLMs) like those seen in LLMs such as Google's Gemini. However, for basic automation tasks, object detection provides the needed info. These models use a deep learning model, typically a Convolutional Neural Network (CNN), that processes the video frame by frame and compares outlying shapes to its model to identify objects.


## Tools
To conduct this project, you will need the following tools.

### Hardware
* RGB camera with a minimum resolution of 600x600 (see [CVM](###CVM)). 
* Computer with a quad-core CPU and 8 or more Gb of RAM.
* Python version 3.9 or greater

### CVM
For our project, we will use YOLO (You Only Look Once) as it is free, easy to use, and provides multiple model options.


## Process
To run YOLO, you will need to choose a model. For this project, we will utilize one of YOLO's built-in models, which vary in performance from nano (n) to extra-large (xl).

### YOLO Installation
To download YOLO we will use pip to install the library into your Python environment using the bash command in the terminal:
'''pip install ultralytics opencv-python'''

Make sure to install it in your local environment. To ensure this, make sure the file path in your terminal is set to your enviroments file path

### Webcam 
To 

## Refrences
[1] G. Jocher et al., “Yolo Object Detection & Segmentation,” Ultralytics Docs, https://docs.ultralytics.com/ (accessed Oct. 30, 2026).






