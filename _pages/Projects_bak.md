---
layout: archive
title: "Projects"
permalink: /Projects/
author_profile: true
---

<div style="display: flex; width: 100%;">
  <!-- 左侧文字内容和标题 -->
  <div style="flex: 3; padding-right: 20px;">
    <h2>Dexterous Hand Embedded Development</h2>  <!-- 添加的标题 -->
    <ul>
      <li>Developed motor drive and motion control for a dexterous hand system using an automotive-grade YTM microcontroller. This involved implementing precise control over current, speed, and position for miniature brushless motors, tailored to the specific needs of robotic applications.</li>
      <li>Implemented cascaded PID control for fingers and palms, improving control accuracy and responsiveness, which are critical for achieving fine motor skills in robotic hands.</li>
      <li>Led the development of monitoring and protection systems to prevent issues including overcurrent, overheating, and motor stalling, ensuring the system operates reliably under various conditions.</li>
      <li>Designed user-friendly interface controls and developed PC communication libraries, facilitating the interaction with the dexterous hand and the integration with other robotic systems.</li>
    </ul>
  </div>
  <div style="flex: 2; display: flex; align-items: center;">
    <div style="flex: 1; margin-right: 10px;">
      <video style="width: 100%; max-height: 100%;" controls>
        <source src="/YD.Huang/files/hand1.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
    <div style="flex: 1;">
      <video style="width: 100%; max-height: 100%;" controls>
        <source src="/YD.Huang/files/hand2.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
</div>

## Autonomous Navigation Perception System for Quadruped Robots Based on Lidar and Machine Vision

<div style="display: flex; width: 100%;">
  <!-- 左侧文字内容 -->
  <div style="flex: 3; padding-right: 20px;">
    <h3>Bachelor thesis project, Advisor: Prof. Yilin Mo, Tsinghua University</h3>
    <ul>
      <li>Configured the system with essential hardware and software components, including Velodyne VLP-16 lidar, Intel RealSense D435i depth cameras, and an Nvidia AGX Orin board, running on Ubuntu 20.04 with ROS Noetic.</li>
      <li>Developed a perception and navigation system for the Unitree Go1 quadruped robot, integrating lidar and machine vision technologies.</li>
      <li>Achieved a localization accuracy of 0.01 meters, enabling the robot to maneuver through gaps as narrow as 0.4 meters.</li>
      <li>Implemented target recognition and tracking capabilities using OpenCV to enhance the robot's interactive and operational abilities.</li>
    </ul>  
  </div>
<div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
    <video style="width: 100%; max-height: 200px; margin-bottom: 20px;" controls>
      <source src="/YD.Huang/files/dog_move.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
    <video style="width: 100%; max-height: 200px; margin-bottom: 20px;" controls>
      <source src="/YD.Huang/files/dog_follow_h264.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
<div style="display: flex; justify-content: flex-start; width: 100%; margin-top: 20px;">
  <img src="/YD.Huang/files/dog.jpg" style="width: 30%; height: auto; margin-right: 10px;">
  <img src="/YD.Huang/files/dog2.jpg" style="width: 30%; height: auto;">
</div>

## Robomaster Robotics Competition

  <div style="display: flex; margin-bottom: 20px;">
    <div style="flex: 3; padding-right: 20px;">
      <h3>Vision Team Leadership:</h3>
      <p>Developed a vision auto-aiming system for different robotic units, enhancing target recognition and tracking with OpenCV and Extended Kalman Filter (EKF). This system not only improved accuracy for fast-moving targets but also automated engagement with energy laser targets, earning multiple competition awards.</p>
    </div>
    <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
      <video style="width: 100%; height: auto;" controls>
        <source src="/YD.Huang/files/Auto_aim.mp4" type="video/mp4">
        Your browser does not support the video tag.
      </video>
    </div>
  </div>
  <div style="display: flex; margin-bottom: 20px;">
    <div style="flex: 3; padding-right: 20px;">
      <h3>Infantry Leadership (2022 Season):</h3>
      <p>Led the development of a control system using FreeRTOS, along with CAN and serial communications, which improved the motion control of an omnidirectional chassis robot and its turret.</p>
    </div>
    <div style="flex: 1;">
      <img src="/YD.Huang/files/Balance.jpg" style="width: 100%; height: auto;">
    </div>
  </div>
  <div style="display: flex; margin-bottom: 20px;">
    <div style="flex: 3; padding-right: 20px;">
      <h3>Sentinel Group Leadership (2023 Season):</h3>
      <p>Implemented mapping, localization, and navigation strategies using Fast-lio under Mid360 LiDAR, which enhanced the robot’s operational capabilities. Managed autonomous attacks and developed defensive strategies, enhancing the robot's tactical responses.</p>
    </div>
    <div style="flex: 1;">
      <img src="/YD.Huang/files/sentry.jpg" style="width: 100%; height: auto;">
    </div>
  </div>


<div style="display: flex; margin-bottom: 20px;">
  <div style="flex: 3; padding-right: 20px;">
    <h3>Unmanned Aerial Vehicle (UAV) Development (2023):</h3>
    <p>Directed the development and control of a large quadcopter using the DJI A3 flight controller, focusing on stable hovering and adaptive control during dynamic conditions such as bullet firing, ensuring consistent performance.</p>
  </div>
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
    <img src="/YD.Huang/files/UAV.jpg" style="width: 100%; height: auto;">
  </div>
</div>
<div style="display: flex; width: 100%; height: 300px;"> <!-- 增加容器高度 -->
  <video style="flex-grow: 1; min-width: 30%; max-width: 100%; height: 100%;" controls> <!-- 调整视频高度和宽度范围 -->
    <source src="/YD.Huang/files/UAV_game.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="flex-grow: 1; min-width: 30%; max-width: 100%; height: 100%;" controls>
    <source src="/YD.Huang/files/UAV_test.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
  <video style="flex-grow: 1; min-width: 30%; max-width: 100%; height: 100%;" controls>
    <source src="/YD.Huang/files/balance_game.mp4" type="video/mp4">
    Your browser does not support the video tag.
  </video>
</div>
## Motion Control and Target Tracking System

<div style="display: flex; width: 100%;">
  <!-- 左侧文字内容 -->
  <div style="flex: 3; padding-right: 20px;">
    <ul>
      <li>Developed a target tracking and motion control system for a 2D gimbal using an STM32F407 microcontroller and DJI M6020 motors, paired with a Hikvision industrial camera and FreeRTOS. Employed OpenCV for vision processing and PID for control.</li>
      <li>Achieved tracking and control accuracy of 0.01m at the sensory distance of over 2m, resulting in a first-place national award and qualification for the Ti Cup recommendation.</li>
    </ul>
  </div>
  <!-- 右侧图片和视频 -->
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
    <video style="width: 100%; max-width: 300px; height: auto;" controls>
      <source src="/YD.Huang/files/motion_control.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>

## Tower crane

<div style="display: flex; width: 100%; align-items: start;">
  <div style="flex: 3; padding-right: 20px;">
    <ul>
      <li>Led the team to a first-place finish at the 2022 National Mechanical Engineering Innovation and Creativity Competition.</li>
      <li>Developed a central rotating tower crane equipped with features for target recognition, automatic grasping, stacking, and obstacle navigation.</li>
      <li>Achieved the competition's fastest completion time of 32 seconds in the finals, showcasing superior mechanical engineering innovation.</li>
    </ul>
  </div>
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
    <video style="width: 100%; height: auto;" controls>
      <source src="/YD.Huang/files/Tower crane.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
## Sound Source Localization System

<div style="display: flex; width: 100%; align-items: start;">
  <div style="flex: 3; padding-right: 20px;">
    <ul>
      <li>Developed a one-dimensional sound source localization system for the 2022 Jiangsu Province College Student Electronic Design Competition.</li>
      <li>Deployed a Max9814 microphone array with Direction of Arrival (DOA) and Fast Fourier Transform (FFT) algorithms for sound tracking.</li>
      <li>Improved accuracy with filtering techniques, achieving a precision of ±0.02m within a 5-meter range.</li>
    </ul>
  </div>
  <div style="flex: 1; display: flex; flex-direction: column; align-items: center;">
    <video style="width: 100%; max-width: 300px; height: auto;" controls>
      <source src="/YD.Huang/files/sound_source.mp4" type="video/mp4">
      Your browser does not support the video tag.
    </video>
  </div>
</div>
## Dispensing Machine Communication Protocol PC Software

- Led the development of a communication protocol software at Changzhou Mingsai Robotics Technology Co., Ltd., enabling efficient interfacing between industrial PCs and PLCs using third-party open-source codes. Supported major protocols including FINS, PROFINET, Ethernet/IP, and DeviceNet, enhancing compatibility across German and Japanese PLCs. Conducted extensive functional and stress testing to ensure robustness and operational stability.

## Intelligent Refillable Pen Core Automatic Feeding Production Line

- Led a project to automate the loading and assembly of three-color pen refills, leveraging C# and MySQL for system control. Integrated industrial cameras for defect detection and synchronized operations with PLCs, which improved production efficiency and quality by automating assembly and eliminating defective units.

## Intelligent Medication Delivery Robot

- Developed an intelligent medication delivery robot for the 2021 National Undergraduate Electronic Design Competition.
- Integrated advanced navigation systems and digit recognition using Yolo-v5 for accurate medication delivery in healthcare settings.
- Included voice announcement capabilities to enhance interaction and effectiveness in operational environments.
