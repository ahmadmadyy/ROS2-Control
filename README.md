# ROS2-Control
A repo that contains a ROS2 control hardware interface

# 🤖 Solo8 ROS 2 Control Hardware Interface

This repository contains a custom ROS 2 `hardware_interface` implementation for the **Solo8 quadruped robot**, integrated with the `ros2_control` framework.

## 📽️ Simulation Video

![Simluation Video](https://github.com/ahmadmadyy/ROS2-Control/blob/main/ros2_control.mp4)

## 📦 Package Overview

- **Robot:** [Solo8 quadruped](https://open-dynamic-robot-initiative.github.io/)
- **Purpose:** Real-time control via `ros2_control` and `controller_manager`
- **Hardware Interface:** Custom `SystemInterface` implementation
- **Communication:** Based on `dynamixel_workbench_toolbox` or custom CAN interface
