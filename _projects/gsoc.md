---
layout: page
title: Industrial robot simulation
description:  in JdeRobot
img: assets/img/gsoc.png
# redirect: https://theroboticsclub.github.io/colab-gsoc2020-Yijia_Wu/2020-08-31-conclusion/
importance: 2
category: Work
---

## Project Introduction
The goal of this project is to develop a set of robot manipulation exercises with incremental complexity for JdeRobot Robotic Academy users. With these exercises, users can gain a better understanding of the processing of a manipulation task which mainly includes perception, planning and control. They can also become more familiar with some popular working frameworks in robotics: ROS, Gazebo, MoveIt, and some well-known open-source computer vision libraries: OpenCV and PCL.

[Project blog](https://theroboticsclub.github.io/colab-gsoc2020-Yijia_Wu/)



### Exercise one: Pick and Place
**Task:** Pick objects from a conveyor and place them to the box with the same color. Objects and Obstacles shape, color and pose are known.   
**Robot:** [IRB120](https://new.abb.com/products/robotics/industrial-robots/irb-120)  
**Gripper:** [robotiq85](https://robotiq.com/products/2f85-140-adaptive-robot-gripper)(two-finger mechanical gripper)  
**Sensor:** None  
[Tutorial](https://jderobot.github.io/RoboticsAcademy/exercises/IndustrialRobots/pick_place)  
**Demonstration Video:** 
<iframe
    width="640"
    height="480"
    src="https://www.youtube.com/embed/kJMPz80w9BM"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

<p></p>

### Exercise two: Machine Vision
**Task:** Pick objects from a conveyor and place them to a box. Objects shape, color are known. The pose of objects should be detected using color and shape filter. The obstacles should be detected from point cloud.   
**Robot:** [UR5](https://www.universal-robots.com/products/ur5-robot/)  
**Gripper:** vacuum gripper(self-made)  
**Sensor:** kinect camera  
[Tutorial](https://jderobot.github.io/RoboticsAcademy/exercises/IndustrialRobots/machine_vision)    
**Demonstration Video:** 
<iframe
    width="640"
    height="480"
    src="https://www.youtube.com/embed/LHq4ZA2lGxQ"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>

<p></p>

### Exercise three: Mobile Manipulator
**Task:** Pick objects on a conveyor and place them to trays on other conveyors. Objects and Obstacles shape, color and pose in world frame are known.  
**Robot:** [MMO-500](https://docs.neobotix.de/display/ROSSim/Robots)(mobile manipulator from Neobotix, combining AGV and UR5)  
**Gripper:** [Modular Grasper](https://www.shadowrobot.com/products/modular-grasper/)(three-finger mechanical gripper from Shadow Robot Company)   
**Sensor:** laser   
[Tutorial](https://jderobot.github.io/RoboticsAcademy/exercises/IndustrialRobots/mobile_manipulation)    
**Demonstration Video:** 
<iframe
    width="640"
    height="480"
    src="https://www.youtube.com/embed/0oNY_UHu2cU"
    frameborder="0"
    allow="autoplay; encrypted-media"
    allowfullscreen
>
</iframe>
