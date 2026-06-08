---
title: 'Drone Swarm Obstacle Avoidance – Collision-Free Navigation of Micro-Drones'

authors:
  - admin

date: '2026-06-08T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']

publication: "Project or Master's Thesis, TH Nürnberg — Mobile Robotics Lab, AerodrOHM"
publication_short: "Mobile Robotics Lab"

abstract: |
  The Crazyflie micro-drones used at the AerodrOHM do not have dedicated onboard sensors
  for environmental perception. To enable safe interaction with people in the shared flight
  space, an external 3D camera is to be installed near the swarm. The goal is a system that
  reliably detects people in the shared flight space and controls the swarm so that drones
  automatically avoid and clear the way.

  In the first step, the 3D camera is to be integrated into a ROS-based system architecture.
  The acquired point cloud data must be filtered, pre-processed, and transformed into an
  appropriate coordinate system. A central aspect is the classification of detected objects:
  the system must reliably distinguish between people and the drones themselves, using
  segmentation and 3D object recognition methods such as cluster-based or learning-based approaches.

  Building on the person detection, a reactive swarm behaviour is to be developed that
  ensures safe coexistence in the shared space. This includes defining safety zones around
  detected persons, dynamically adapting flight paths, and coordinating evasive manoeuvres
  within the swarm to also avoid collisions between drones. Practical testing takes place
  in the AerodrOHM flight space.

summary: 'Development of a system for collision-free navigation of Crazyflie drone swarms using an external 3D camera, ROS integration and reactive swarm behaviour. Testing in the AerodrOHM flight space.'

tags:
  - Drones
  - Swarm Robotics
  - ROS
  - Point Clouds
  - Person Detection
  - Obstacle Avoidance
  - Crazyflie
  - AerodrOHM
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
  caption: 'Crazyflie micro-drones at AerodrOHM'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Work Packages

- Integration and calibration of the external 3D camera
- Processing, filtering and transformation of point cloud data
- Development of a classification to distinguish between persons and drones
- Design and implementation of a reactive swarm behaviour with safety zones
- Test and evaluation in the flight space with real persons

## Requirements

- Programming skills (Python and/or C++)
- Ideally some experience with ROS
- Interest in sensor integration, point cloud processing and perception methods

This topic can be completed as a **project or master's thesis** subject to agreement.

## Contact

**Prof. Dr. Christian Pfitzner** — Mobile Robotics Lab, TH Nürnberg Georg Simon Ohm
[christian.pfitzner@th-nuernberg.de](mailto:christian.pfitzner@th-nuernberg.de)
