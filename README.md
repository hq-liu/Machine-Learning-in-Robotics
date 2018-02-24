# Machine Learning algorithms applied in modern real robots

The packaged includes several most popular used machine learning algorithm applied in the real robot, all algorithm 
and models are trained based on the data obtained from real robot. Those algorithms are the fundamental structures for the visual SLAM project. 

All packages include reports so that for better algorithm clarification and result showing.


Object Detection and Estimation
-------------------------------

Detect interested objects in the image via GMM and GM model, also measure the physical information of the objects in the real world.


UKF for Camera Pose Tracking
----------------------------

Completed Unscented Kalman Filter to estimate the robot orientation, and finally built a panorama with images.


SLAM
----

Based on the lidar scan data from the ground robot, using log-odds grid map to estimate 2D map and simulate robot walking trajectory.


Reinforcement Learning
----------------------

Implemented policy gradient method to estiamte the optimal trajectory of robot within a certain environment with step rewards, also built 
deep network using tensorflow to train and solve Cart-pole game problem.


Gesture Recognition using HMM
-----------------------------
Using IMU sensor readings from gyroscopes and accelerometers to train a set of Hidden Markov Models and recognize different robot arm motion gestures. And finally should be able to classify unknown arm motions in real-time using algorithm.  
