---
title: 'Markerless Indoor Localization of a Drone without GNSS'

authors:
  - admin

date: '2026-06-15T00:00:00Z'
doi: ''
publishDate: '2026-06-15T00:00:00Z'

publication_types: ['thesis']
status: 'reserviert'

publication: "Project or Bachelor's Thesis, TH Nürnberg — Mobile Robotics Lab, AerodrOHM"
publication_short: "Mobile Robotics Lab"

abstract: |
  The drone used at the AerodrOHM currently determines its position via an external,
  marker-based tracking system. While this provides very accurate poses, it requires a
  permanently installed, instrumented flight space and is not available outside of it. The
  goal of this thesis is to enable the existing drone to localize itself indoors without GNSS
  and without markers, using only its onboard sensors.

  The work builds directly on the existing drone and the established ROS-based system
  architecture. In a first step, suitable onboard sensors (camera, IMU, optionally an
  optical-flow or depth sensor) are selected and integrated. Based on this, a markerless
  localization method is implemented — for example visual-inertial odometry (VIO) or a
  visual-SLAM approach — that continuously estimates the drone's ego-motion and feeds it into
  the flight controller.

  Finally, the achieved accuracy and robustness are systematically evaluated. The existing
  marker-based tracking system at the AerodrOHM serves as ground truth, against which the
  markerless solution is compared in flight experiments.

summary: 'The drone used at the AerodrOHM currently localizes via external markers. The goal is a markerless, GNSS-free indoor localization using only onboard sensors (visual-inertial odometry / SLAM), building on the existing platform.'

tags:
  - Drones
  - Indoor Localization
  - GNSS-denied
  - Visual-Inertial Odometry
  - SLAM
  - ROS
  - Computer Vision
  - AerodrOHM
  - Bachelorarbeit
  - Projektarbeit

categories:
  - Bachelorarbeit
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
  caption: 'Drone in the AerodrOHM flight space'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Description

The drone used at the AerodrOHM currently determines its position via an external,
marker-based tracking system. This provides very accurate poses but requires a permanently
installed, instrumented flight space. The goal of this thesis is a markerless, GNSS-free
indoor localization based solely on onboard sensors, so that the drone can fly independently
of the external tracking. The work builds on the existing drone and the established ROS system
architecture.

## Work Packages

- Familiarization with the existing drone platform and the marker-based tracking system at the AerodrOHM
- Selection and integration of suitable onboard sensors (camera, IMU, optionally optical-flow or depth sensor)
- Implementation of a markerless, GNSS-free localization method (e.g. visual-inertial odometry or visual SLAM)
- Integration into the existing ROS system architecture and flight control
- Evaluation of accuracy and robustness against the marker-based tracking as ground truth
- Flight experiments and documentation of the results at the AerodrOHM

## Requirements

- Programming skills (Python and/or C++)
- Ideally some experience with ROS / ROS 2
- Basic knowledge of computer vision and/or state estimation (e.g. Kalman filter)
- Interest in drones, sensor integration and localization
- Independent and diligent way of working

This topic can be completed as a **project or bachelor's thesis** subject to agreement.

## Supervision

| Role       | Name                         | E-Mail                                 |
|------------|------------------------------|----------------------------------------|
| Supervisor | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
