---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Computer Science, University of Lincoln, UK, 2024
* M.S. in Mechatronics Engineering, Sharif University of Technology, Iran, 2017
* B.S. in Mechnaical Engineering, Amirkabir University of Technology, Iran, 2014

Work experience
======
* Postdoctoral Research Associate in Robotics & Intelligent Systems
  * University of Lincoln, UK (2023 - 2024)
  * Focus: Robotic Navigation Software Development
  * Developed navigation software for a weed removal robot using ArduPilot and Mavros. Integrated black weed detection vision system for mechanical tool control. Digital twinning of plant by combining UGV and UAV 3D pointcloud data.

* Robotic Manipulation Research Engineer
  * University of Lincoln, UK (2022 - 2023)
  * Focus: Enabling Tactile Feedback for Strawberry Picking Gripper
  *  Developed a grip force controller using a customized vision-based tactile sensor.
    Implemented real-time slip detection and slip avoidance control.
    Implemented model predictive control for flexible object manipulation.

* Robotic Software Engineer
  * Agaricus Robotics, UK (2021 - 2022)
  * Focus: Autonomous Mushroom Harvesting System
  * Performed data collection for training a multi-modal mushroom pose estimation network.
    Utilized ROS, MoveIt, and OpenCV for motion planning and system integration.

* Teleoperation Robotic Engineer
  * Sina Robotics, Iran (2017 - 2019)
  * Focus: Orthopedic Surgical Teleoperation System
  * Developed a bilateral teleoperation controller for femur fracture surgery using Novint Falcon.
    Conducted kinematic modeling of parallel leader and follower robots.

  
Skills
======
* AI & Robotics: 
  * ROS, MoveIt, PyTorch, TensorFlow, Keras, PyBullet, MuJoCo, OpenCV
* Programming:
  * Python , C++, MATLAB, GitHub, Docker
* Hardware:
  * Franka, UR3, Hunter SE, GelSight, uSkin, RealSense, AlegroHand, RightHand
* Software Tools:
  * LlamaIndex, OpenAI, Stability.ai, LangChain, Scikit-Learn, Pandas, Scipy

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
