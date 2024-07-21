# Car Detection in Video Using Background Subtraction and Optical Flow

This repository contains code for detecting moving cars in a video using two different approaches: **background subtraction** and **optical flow**. Each method is implemented in a separate script, and the results are saved as output videos.

## Overview

Detecting moving objects, particularly cars, in video sequences is a fundamental task in computer vision. This repository provides two methods to accomplish this task:
1. **Background Subtraction**: Identifies moving objects by comparing each frame of the video with a background model.
2. **Optical Flow**: Detects moving objects by estimating the motion of pixels between consecutive frames.

### Background Subtraction Demo
Click on the below image to check the results:
[![Watch the video](https://github.com/EhtishamAshraf/object_detection_MATLAB/blob/main/background_subtraction.PNG)](https://youtu.be/_QAfJW_9C4E)

### Optical Flow Demo
Click on the below image to check the results:
[![Watch the video](https://github.com/EhtishamAshraf/object_detection_MATLAB/blob/main/optical_flow.PNG)](https://youtu.be/Q3JwrSOYsh8)

The bounding boxes around detected cars display a numerical value inside them. This value represents the mean intensity of the optical flow in the horizontal direction. The optical flow vector field gives information about the movement of objects between consecutive frames.
1. Positive values of mean intensity indicate that the detected cars are moving to the right.
2. Negative values of mean intensity indicate that the detected cars are moving to the left.

## Requirements

To run the scripts in this repository, you need the following:
- MATLAB
- Image Processing Toolbox
- Computer Vision Toolbox

## Installation

Clone this repository to your local machine:
```sh
https://github.com/EhtishamAshraf/object_detection_MATLAB.git
