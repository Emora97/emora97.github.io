---
layout: post
title: "Drone Automation Using the Crazyflie 2.1+"
description: "Development of an autonomous flight framework for the Bitcraze Crazyflie 2.1+, including trajectory generation, onboard state estimation, flight data logging, and a repeatable testing environment for evaluating lightweight control strategies. External trajectory validation is performed through a companion OpenCV-based tracking pipeline."
skills:
  - Python Interfacing
  - Crazyflie Development
  - Autonomous Flight Control
  - Flight Data Logging
  - Hardware Debugging
main-image: /dronearuco.png
---

## Repository

**GitHub:** [Drone Automation](https://github.com/Emora97/Drone-Automation)

## Overview

This project establishes a repeatable experimental framework for autonomous microdrone flight using the Bitcraze Crazyflie 2.1+ platform. The software supports trajectory execution, onboard telemetry logging, and post-processing for performance evaluation.

A companion OpenCV-based computer vision pipeline is maintained separately to provide external trajectory validation and ground-truth comparison using ArUco markers and markerless tracking techniques.

