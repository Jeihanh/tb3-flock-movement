# TURTLEBOT3 FLOCK MOVEMENT

Created by: TurtleBot3 Group 

Google Drive: [TurtleBot3 Flock Movement Files](https://drive.google.com/drive/folders/1Acln2Nx1pVWzBOU7wtAM5d3VY9nPb5Mz)

## Table of Contents

- [Introduction](#introduction)
- [Requirements](#requirements)
- [Installation](#installation)
- [How to Run](#how-to-run)

## Introduction

Instructions on how to successfully run the code for TurtleBot3 Flock Movement. This file includes hardware and software requirements, how to install the necessary packages, and steps on running the code from the terminal.

## Requirements

- 2 TurtleBot3 with Raspberry Pi running on Ubuntu 18.04
- 1 Remote PC running on Ubuntu 18.04 with ROS Melodic

## Installation

TurtleBot3 & Remote PC setup refer to chapter 3 (Quick Start Guide) of the official Robotis e-Manual: [TurtleBot3 Overview](https://emanual.robotis.com/docs/en/platform/turtlebot3/overview/)

## How to Run

How to run the code:

- To run the code, open the terminal and write the following command:

    ```bash
    $ rosrun test tb3_flock.py
    ```

- This is possible because we created our own package in the catkin workspace.

- To create a new package, we use `catkin_create_pkg`. Below is the following syntax:

    ```bash
    $ catkin_create_pkg <package_name> dependency1 dependency2 ...
    ```

- Here is an example of how to use it:
    
    ```bash
    $ catkin_create_pkg test rospy roscpp
    ```

For more explanation, refer to [ROS Wiki: rospy tutorials](http://wiki.ros.org/rospy_tutorials/Tutorials/Makefile)
