---
permalink: /
title: ""
excerpt: "Yaotian Zhang - robotic perception, state estimation, SLAM, sensor fusion, and autonomous navigation."
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class='anchor' id='about-me'></span>

I am an undergraduate student in Electronic Information Engineering at **Southwest Jiaotong University**, where I am pursuing a B.Eng. degree and expect to graduate in June 2027. My GPA is **3.68/4.00** (91.19/100), and I rank **13th out of 79 students** (top 16%).

My work focuses on robotic perception, state estimation, SLAM, sensor fusion, computer vision, and autonomous navigation. I have developed and evaluated perception and localization systems on physical quadruped robots, with an emphasis on real-time performance and reliable deployment.

[[Email]](mailto:yaotianzhang94@gmail.com) &nbsp; [[CV]](/files/Yaotian-Zhang-CV.pdf) &nbsp; [[GitHub]](https://github.com/dandelionskyy)


<span class='anchor' id='-research'></span>

# 🔬 Research

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Robotics 2025</div><img src='images/lidar-map.png' alt="LiDAR point-cloud map" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### Contact-Aware SLAM Optimization for Legged Robots

*Mar. 2025 - Aug. 2025*

I developed a contact-aware optimization method for legged-robot SLAM. Foot-end sensors estimate contact states, and a state machine adaptively switches constraints in Fast-LIO2. RANSAC-based ground-plane estimation provides plane constraints to reduce vertical drift.

- **Method:** Fast-LIO2, RANSAC, state machine, ground-plane constraints
- **Result:** average processing time below 75 ms and approximately 2 cm z-axis accuracy on a physical quadruped robot

</div>
</div>

### Urban Traffic Risk Prediction and Assessment

*May 2024 - Jul. 2025*

I contributed to a traffic-scene perception and risk-assessment pipeline using more than **300,000 annotated intersection images**. YOLOv8 detects traffic participants, DeepSORT tracks their trajectories, and an SVM classifies traffic risk from the extracted features.

- **Detection:** mAP@0.5 of 0.934; vehicle detection accuracy above 0.90; vulnerable-road-user AP above 0.50
- **Risk assessment:** 98% classification accuracy and an F1 score of 0.96


<span class='anchor' id='-projects'></span>

# 🤖 Projects

### Quadruped Obstacle Perception and Localization

*Mar. 2025 - Aug. 2025*

I built an obstacle-perception and localization system for an 8-DoF quadruped robot using a depth camera, IMU, AprilTag, and Stanley controller. The system combines depth-camera and IMU measurements with 6-DoF tag localization and segmented target correction.

- **Result:** error below 1 cm within 3 m, below 5 cm within 8 m, and processing latency below 10 ms
- **Validation:** deployed and tested on a physical quadruped robot
- [[Code]](https://github.com/dandelionskyy/depth_camera_ws)

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Navigation 2025</div><img src='images/navigation-map.png' alt="Quadruped navigation map" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

### Quadruped Localization, Mapping, and Navigation

*Mar. 2025 - Jun. 2025*

I integrated a complete localization, mapping, and autonomous-navigation stack for a 12-DoF quadruped robot. Livox Mid360 data is processed by Fast-LIO2 with statistical outlier removal, Fast-LIO-Localization provides relocalization, and Nav2 handles planning and control.

- **Result:** localization accuracy within 3 cm
- **Validation:** autonomous navigation through a physical obstacle course
- [[Code]](https://github.com/dandelionskyy/fast-lio-nav-Obstacle)

</div>
</div>


<span class='anchor' id='-education'></span>

# 📖 Education

- *Sep. 2023 - Jun. 2027 (expected)*, **Southwest Jiaotong University**, B.Eng. in Electronic Information Engineering
  - GPA: 3.68/4.00; overall score: 91.19/100
  - Rank: 13/79 (top 16%)


<span class='anchor' id='-honors'></span>

# 🎖 Honors and Awards

- *2025*, **National First Prize**, 24th ROBOCON Bionic Leg Challenge (Indoor Obstacle Course)
- *2024*, **Honorable Mention (H Prize)**, Mathematical Contest in Modeling / Interdisciplinary Contest in Modeling
- *2024*, **National First Prize**, MathorCup Mathematical Modeling Challenge
- *2024*, **Provincial First Prize**, Contemporary Undergraduate Mathematical Contest in Modeling
- **Chinese Invention Patent (Granted):** Wing Structure Design for Unmanned Aerial Vehicles


<span class='anchor' id='-experience'></span>

# 💻 Experience

- *Aug. 2025 - Aug. 2026*, **Visual Algorithm Group Leader**, ROBOCON School Robotics Team
  - Led perception and localization integration, field testing, and system debugging for competition robots.


<span class='anchor' id='-skills'></span>

# 🛠 Skills

- **Programming:** C++, Python, MATLAB, C
- **Robotics:** ROS 1/2, Nav2, Fast-LIO2, VINS-Mono, Gazebo, MuJoCo
- **Perception:** LiDAR-inertial odometry, AprilTag, OpenCV, PCL
- **Machine Learning:** PyTorch, YOLOv8, DeepSORT, SVM
- **Hardware:** STM32, NVIDIA Jetson Orin Nano
