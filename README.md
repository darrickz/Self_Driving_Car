# Self-Driving Car

---
<font size="3">
    
First apply computer vision and deep learning to automotive problems, including detecting lane lines, predicting steering angles, and more.
Next, learn about sensor fusion, to filter data from an array of sensors in order to perceive the environment. Then, you'll work with a team to program Carla, Udacity’s real self-driving car. 
</font>

---

## Projects

### Project 1: Advanced Lane Line Detection

In this project, the goal is to write a software pipeline to identify the lane boundaries in a video
* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position

<figure>
    <kbd>
    <img  src="./images/advanced_lane.gif" alt="Drawing" style="width: 500px;"/>
    </kbd>    
    <p align="center">Advanced Lane Line Detection</p>
</figure>

<table><tr>
<td>
<figure>
    <img  src="./images/advanced_lane.gif" alt="Drawing" style="width: 500px;"/>
    <center>Advance Lane Detection</center>
</figure></td>

<td><figure>    
    <kbd>
    <img  src="./images/cloning.gif" alt="Drawing" style="width: 500px;"/>
    </kbd>
    <center>Behavior Cloning</center>
</figure>
  </td>  </tr></table>


---

### Project 2: Traffic Sign Classification

In this project, a convolutional neural network is implemented to classify traffic signs. The traffic sign images is the German Traffic Sign Dataset.

   * Load the data set
   * Explore, summarize and visualize the data set
   * Design, train and test a model architecture
   * Use the model to make predictions on new images
   * Analyze the softmax probabilities of the new images
   * Summarize the results with a written report


<figure>
    <img  src="./images/traffic_sign.png" alt="Drawing" style="height: 500 width: 1000px;"/>
    <center>Data Distribution</center>


### Project 3: Extended Kalman Filter


Utilize a kalman filter to estimate the state of a moving object of interest with noisy lidar and radar measurements.

<figure>
    <kbd>
    <img  src="./images/eklm.gif" alt="Drawing" style=" width: 500px;"/></kbd>
</figure>


### Project 4: Kidnapped Vehicle

Figure out the Vehicle location based on map, a noisy GPS estimate, and other sensors data

<figure>
    <img  src="./images/kidnap.gif" alt="Drawing" style="width: 450px;"/>
    <center>Sagemaker Architecture</center>
</figure>



### Project 5: Behavioral Cloning

Using deep neural networks and convolutional neural networks to clone driving behavior. Model is trained, validated and tested using Keras, and output a sterring angle to an autonomous vehicle

<figure>
    <img  src="./images/cloning.gif" alt="Drawing" style="width: 450px;"/>
    <center>Behavioral Cloning</center>
</figure>



### Project 6: PID Control

This project is to develop a PID controller given the cross track error (CTE) and the velocity (mph) provided by simulator. The goal is the car can be successfully naviated around the track

<figure>
    <img  src="./images/pid.gif" alt="Drawing" style="width: 450px;"/>
    <center>PID Control</center>
</figure>



### Project 7: Path Planning

The goal of this project is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. The car's localization and sensor fusion data are given, there is also a sparse map list of waypoints around the highway.

<figure>
    <img  src="./images/path_planing.gif" alt="Drawing" style="width: 450px;"/>
    <center>Path Planning</center>
</figure>



### Project 8: Programming Real Car

The goal of this project is to safely navigate around a virtual highway with other traffic that is driving +-10 MPH of the 50 MPH speed limit. The car's localization and sensor fusion data are given, there is also a sparse map list of waypoints around the highway.

<figure>
    <img  src="./images/capstone.gif" alt="Drawing" style="width: 450px;"/>
</figure>


