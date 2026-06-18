---
title: '2R Robot Arm Lab Experiment – Gravity Compensation and Reinforcement Learning'

authors:
  - admin

date: '2026-06-08T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']
status: 'offen'

publication: "Project or Master's Thesis, TH Nürnberg — Mobile Robotics Lab"
publication_short: "Mobile Robotics Lab"

abstract: |
  The M-IAS (Intelligent Autonomous Systems) master's programme at TH Nürnberg requires a
  new lab experiment for the "Intelligent Robotics" practical course that demonstrates
  fundamental concepts of control theory and machine learning in a hands-on setting.
  The goal of this thesis is to build a two-link robot arm (2R kinematics) based on two
  BLDC motors, serving as a versatile demonstration platform for gravity compensation
  and reinforcement learning.

  On the hardware side, both joints are to be equipped with BLDC motors and suitable motor
  drivers (e.g. ODrive or VESC). The mechanical structure of the arm segments is to be
  designed and manufactured, considering stiffness, weight and accessibility for students.
  Encoders provide the necessary position and velocity feedback for control.

  On the software side, forward and inverse kinematics are to be implemented first, along
  with model-based gravity compensation that compensates for the weight of the arm segments
  in real time, keeping the arm floating in any position. This physically intuitive experiment
  forms the entry point for students into model-based control.

  Building on this, a reinforcement learning demo is to be developed where an agent learns
  to move the arm to a target position. A ROS-based system architecture is to be established
  supporting both real hardware and a simulation environment (e.g. Gazebo or MuJoCo) for
  RL training. Lab instructions for student use in M-IAS are to be prepared.

summary: 'Building a 2R robot arm with BLDC motors as an M-IAS lab experiment: model-based gravity compensation and reinforcement learning demo with ROS integration and simulation support.'

tags:
  - Robotics
  - BLDC
  - Gravity Compensation
  - Reinforcement Learning
  - ROS
  - Kinematics
  - Control Theory
  - M-IAS
  - Lab Experiment
  - Masterarbeit
  - Projektarbeit

categories:
  - Masterarbeit
  - Projektarbeit

featured: true

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

image:
  caption: ''
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Motivation

The "Intelligent Robotics" practical course in the M-IAS master's programme currently lacks
a hands-on experiment bridging classical model-based control and modern learning-based methods.
A 2R robot arm with torque control offers exactly this: students first experience the physical
effects of gravity on the real system, then learn how an RL agent solves the same task in a
data-driven way.

## Work Packages

**Hardware**
- Selection and commissioning of BLDC motors and motor drivers (e.g. ODrive / VESC)
- Mechanical design and fabrication of arm segments (CAD, 3D printing or aluminium profile)
- Integration of encoders and wiring

**Software & Control**
- Implementation of forward and inverse kinematics
- Model-based gravity compensation controller (real-time torque compensation)
- ROS integration: topics, services and ros2_control

**Reinforcement Learning**
- Building a simulation environment (Gazebo or MuJoCo) for RL training
- Training an agent (e.g. PPO / SAC) on a target-reaching task
- Sim-to-real transfer and evaluation on the real arm

**Documentation**
- Creating lab instructions for use in the M-IAS practical course

## Requirements

- Knowledge of control theory and robotics (kinematics, dynamics)
- Programming skills in Python and/or C++
- Ideally experience with ROS
- Interest in machine learning and reinforcement learning
- Enthusiasm for hands-on hardware work and prototyping

This topic can be completed as a **project or master's thesis** subject to agreement.

## Supervision

| Role       | Name                         | E-Mail                                 |
|------------|------------------------------|----------------------------------------|
| Supervisor | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
