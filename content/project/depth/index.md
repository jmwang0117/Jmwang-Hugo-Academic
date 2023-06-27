---
title: ⏳ Design of Obstacle Avoidance Robot Based on Monocular Depth Estimation
summary: <b style="color:#008080">Undergraduate Final Year Project</b></br> 
 <b style="color:#E08040">Junming Wang,</b> Supervisor - *Prof.Song Wang*  </br>
 

tags:
- Computer Vision
date: "2022-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

url_video: 'https://drive.google.com/file/d/1vJjF6xwiPW7VbAZZVYZ4S6TTLtbcAFoV/view?usp=sharing'
url_slides: 'https://drive.google.com/file/d/12gzT7Gkw6DHhwf2LLzj5EWipf_j8sqXM/view?usp=sharing'

---
Autonomous navigation and obstacle avoidance of mobile robots has become a research hotspot due to the rapid development of autonomous driving and smart warehousing. Traditional robot navigation and obstacle avoidance are frequently performed using road sign navigation techniques such as autonomous tracking and magnetic wire. Such methods are less adaptable and maneuverable, and they cannot meet the complex and changing business needs of real-world industrial scenarios. Furthermore, previous research on mobile robots has mostly used special software or self-developed platforms for development, so such robots lack openness, portability, and scalability. With the maturation of computer vision and high-precision sensor technology, this thesis develops an open source mobile robot suitable for indoor and outdoor multiple scenes with navigation and obstacle avoidance functions in response to the aforementioned problems.


This thesis's main research contents and findings are as follows:


1. The laser SLAM technology and the robot positioning and path planning algorithm are studied. Firstly, the basic principle of Gmapping algorithm based on RBPF is discussed; secondly, the sensor fusion algorithm based on extended Kalman filter is studied, which can use inertial sensor data and encoder data fusion to obtain high-precision odometer data; then AMCL positioning is studied algorithm to realize the real-time positioning function in the process of robot navigation and obstacle avoidance; finally, the deployment and application of Dijkstra algorithm and DWA algorithm in the overall travel route and local travel route planning of the robot are realized, and the navigation is completed by combining the move_base framework provided by ROS with obstacle avoidance.

2. The monocular depth estimation algorithm is investigated in order to address the problem that two-dimensional lidar is only suitable for indoor environments and has significant limitations. At the same time, because embedded devices cannot deploy deep neural networks due to their own limitations , this thesis compares two lightweight depth estimation neural network models: PyDNet and FaseDepth, as well as a more generalized monocular depth estimation model: MiDaS, and uses the ROS2 operating system and TensorRT to complete the compression, optimization, and deployment of the MiDaS model , resulting in real-time depth estimation.

3. The mobile robot's sensor selection and design were completed, and a two-wheel differential robot based on ROS was finally completed. Experiments in navigation and obstacle avoidance are conducted in indoor multi-scene situations (dormitories, corridors), and the results show that the robot can construct indoor grid maps, route plan, and obstacle avoidance functions. Obstacle avoidance experiments using monocular depth estimation are conducted in a variety of indoor and outdoor scenarios. The robot can complete real-time depth estimation and combine depth data to complete obstacle avoidance work with the monocular camera.

   
Based on laser SLAM and monocular depth estimation, the mobile robot can perform autonomous navigation and obstacle avoidance in indoor and outdoor multi-scene environments. It is high, open source, and simple to implement, and it can be used as a reliable support for navigation and obstacle avoidance in autonomous driving scenarios.
