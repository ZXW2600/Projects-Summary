# Project Summary

Author： Xinwei Zhao ([zhaoxinwei74@gmail.com](zhaoxinwei74@gmail.com))

## 0. RoboMaster University AI Challenge

This project aims to design a robot system which can perform localization, navigation, auto aim and decision making in an indoor environment.

I finished the simulation, localization and navigation parts.

The simulation is now released (https://github.com/XDUZero2Hero/zero2hero_rmua2022_simulation).

![ezgif.com-gif-maker](Readme.assets/ezgif.com-gif-maker.gif)

## 1. Reproduction of  Roadmap system

It is a simple SLAM system based on monocular-camera. Here is the simulation and the mapping output.

![sim_up](Readme.assets/sim_up.gif)

![mapping_up](Readme.assets/mapping_up.gif)

I used a modified version of car_demo [repo](https://github.com/ZXW2600/car_demo_fork) (to make it running properly on ros noetic).

Mapping part of code will be released soon.

## 2. Automated Guided Vehicle Located By Vision

We designed a robot equipped with 4-dof arm and omni base, which can perform the task of picking and placing. The only sensor we used is monocular camera and odom.

I finished the hardware design, localization, navigation and all the control part. 

Here is the demo.

![lv_0_20220517151830_Trim](Readme.assets/lv_0_20220517151830_Trim.gif)

And here is our vision pipeline

![image-20220531113035042](Readme.assets/image-20220531113035042.png)

## 3. Automatic Sorting Dustbin Using Intrinsic Property

Almost all the garbage classification is done by using image classification, which can not fully describe a garbage. Our system use Intrinsic property as many as possible, such as weight, density, magnetic inductivity, water content and hardness, to judge a garbage's class, which has higher accuracy.

I designed the classification framework, the sensor and the mechanism. Here is the demo.

![lv_0_20220517151830_Trim](Readme.assets/dustbin.gif)

