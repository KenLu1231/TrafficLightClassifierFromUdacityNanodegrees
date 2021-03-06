# Introduction

This is the repo for the final project of the Udacity Intro to Self-Driving Cars Nanodegree Program: **Traffic Light Classifier**. For more information about the project, see the project introduction <a href="https://classroom.udacity.com/nanodegrees/nd113/parts/3407b17c-2111-4484-bfb2-1725cf619a5c/modules/59f59fcc-7e98-4700-a7ca-e8153a5e9857/lessons/82fc3a22-eb21-42bd-8037-f89844a4c69b/concepts/55f82fd2-96bd-4a80-ae5b-2a8ccf016a46">here</a>.

# Project Overview

Three main implementations for this project are :
1. **helpers.py** loads in images which is provided by Udacity and their labels and places them in a list.
2. **test_functions.py** tests the _one hot encode_ and if any misclassified images are red but mistakenly classified as green.
3. **Traffic_Light_Classifier.py** executes the main function _get_misclassified_images_ to calculate the accuracy of the algorithm.

There also are 235 training images and 290 test images provided by Udacity.

# Usage
  
1. Clone the project repository.

```

git clone https://github.com/KenLu1231/TrafficLightClassifierFromUdacityNanodegrees.git

```

2. Run **Traffic_Light_Classifier.py**.

# Library information

Library     | Version 
------------|------------
opencv      | 4.5.1
matplotlib  | 3.3.4
IPython     | 7.16.1
