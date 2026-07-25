# Aydin Orhan

Robotics engineer based in London. Currently working at UCL as a research assistant focused on underwater SLAM, and a teaching assistant for COMP0182 (Real-world Multi-Agent Systems). I led the lab sessions during the 2025-26 cohort and I am rewriting the lab materials for 2026-27. I completed BSc Software Engineering (Hons) at the University of Portsmouth and Systems Engineering for the IoT MSc at UCL. 

## What I'm working on

Building an autonomous ROS 2 rover from the hardware up, porting the PiCar drivers and wrapping them for ROS 2, and working toward fused odometry, AMCL localisation, and vision-based navigation. 

I am implementing an error-state Kalman filter in C++ from Solà's tutorial, to run on the rover. 

## Focus areas

- Robotics — ROS 2, Nav2, SLAM, multi-agent navigation
- Backend & full-stack — Python, FastAPI, MQTT, PostgreSQL, Docker, Azure IoT, CI
- Embedded — Linux on ARM, I2C / SPI / UART, hardware bring-up.

### Selected projects

- **[IoT-task-tracker](https://github.com/aydinao/IoT-task-tracker)** — a distributed, IoT-enabled task system built incrementally: CLI → REST API → MQTT → edge. Layered architecture, Dockerised, with CI and a full test suite.
- **[mapf-nav2-ros2](https://github.com/aydinao/mapf-nav2-ros2)** — autonomous TurtleBot3 navigation in ROS 2 / Nav2: Cartographer SLAM, AMCL localisation, and named-waypoint navigation.
- **[stella-vslam-kitti](https://github.com/aydinao/stella-vslam-kitti)** — visual SLAM on the KITTI dataset with Stella-VSLAM, plus a hands-on exploration of FAST, BRIEF, and ORB feature detection.
- **[picar-4wd](https://github.com/aydinao/picar-4wd-ros2-jazzy)** — bringing up the SunFounder PiCar-4WD on Ubuntu 24.04 with ROS 2 Jazzy: embedded Linux, I2C, and an undocumented HAT reset fix.

📍 London · UCL
