---
title: 🤖 Text Recognition Control Drone
summary: <b style="color:#008080">The University of Hong Kong Project</b></br> 
 <b style="color:#E08040">Junming Wang,</b> Supervisor - *Prof.Heming Cui*  </br>
 

tags:
- Robotics
date: "2022-09-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

url_video: 'https://drive.google.com/file/d/1KYt9QsPayI0538ku6jemxfzs_IUHUx5l/view?usp=sharing'


---
As a developer in the field of drone technology, I have observed some limitations in the existing remote control methods for operating unmanned aerial vehicles (UAVs). These limitations include the need for specialized equipment and the steep learning curve associated with mastering the controls. Additionally, traditional remote control methods may not be suitable for certain applications, such as indoor navigation or complex environments where precise control is required.

To address these challenges, I have developed a text-based control system for UAVs, which offers several advantages over traditional methods. Firstly, it simplifies the control process by allowing users to input commands through text, eliminating the need for specialized hardware and reducing the learning curve. Secondly, real-time text recognition using EasyOCR enables quick and accurate command execution, improving the overall efficiency and precision of drone control.

My workflow for implementing this text-based control system can be described in the following steps:

1. Utilizing EasyOCR for real-time text recognition: I employ EasyOCR to identify and extract text from images or video feeds, which serves as the input for controlling the UAV.

2. Sending the recognized text to the `/text_result` topic: Once the text is recognized, it is transmitted to the `/text_result` topic, which serves as a communication channel for further processing.

3. Mapping the text to specific actions: Based on the received text, I create a mapping system that translates the commands into corresponding actions for the UAV. This can include simple movements like ascending, descending, or rotating, as well as more complex manoeuvres.

4. Utilizing MAVROS to send the actions to the flight controller: After mapping the text to specific actions, I use MAVROS, a ROS-based middleware, to communicate with the drone's flight controller and execute the desired actions.

By following this workflow, I have successfully developed a text-based control system for UAVs that addresses the limitations of traditional remote control methods and offers a more accessible, efficient, and precise alternative for drone operation.
