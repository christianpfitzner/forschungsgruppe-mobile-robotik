---
title: 'Grasping Unknown Components for Robotic Assembly'

authors:
  - admin

date: '2026-09-07T00:00:00Z'
doi: ''
publishDate: '2026-09-07T00:00:00Z'

publication_types: ['thesis']
status: 'offen'

publication: "Bachelor's, project or master's thesis, TTZ Nürnberger Land"
publication_short: "TTZ Nürnberger Land"

abstract: |
  Frequent component revisions pose a challenge for industrial assembly processes. With every
  change cycle, the design, colour and material of a component may change. In robotic assembly,
  this challenge creates a demand for robots capable of adaptation.

  The aim of this thesis is to overcome the limitation to previously known objects. An approach
  for detecting unknown objects and computing their grasp poses is to be developed and
  subsequently compared with existing approaches.

  Adaptability can be achieved by combining visual sensing with methods of artificial
  intelligence. RGB and depth cameras form the interface between the robotic system and its
  environment. The resulting image data can be analysed using methods of artificial
  intelligence, e.g. neural networks, in order to detect and then grasp unknown components.

summary: 'Development of an approach for detecting unknown components and computing their grasp poses using RGB/depth cameras and neural networks. Validation on a robot cell with a collaborative robot at TTZ Nürnberger Land.'

tags:
  - Robotic Assembly
  - Grasping
  - Object Detection
  - Deep Learning
  - ROS
  - TTZ Nürnberger Land
  - Bachelorarbeit
  - Projektarbeit
  - Masterarbeit
  - M-APR

categories:
  - Bachelorarbeit
  - Projektarbeit
  - Masterarbeit
  - M-APR

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

Frequent component revisions pose a challenge for industrial assembly processes. With every change cycle, the design, colour and material of a component may change. In robotic assembly, this challenge creates a demand for robots capable of adaptation.

## Topic Area

For assembly, the robot system has access to a stored assembly plan. This plan contains the component designations, the assembly sequence and the region, the latter serving to roughly localise the assembly position. In order to assemble components under these boundary conditions, the components at hand must be detected, matched to a component designation and their grasp pose determined. To date, neural networks are trained on already known objects. They are therefore limited with regard to capturing new, unknown components.

## Description

The aim of this thesis is to overcome the limitation to previously known objects. An approach for detecting unknown objects and computing their grasp poses is to be developed and subsequently compared with existing approaches.

Adaptability can be achieved by combining visual sensing with methods of artificial intelligence. RGB and depth cameras form the interface between the robotic system and its environment. The resulting image data can be analysed using methods of artificial intelligence, e.g. neural networks, in order to detect and then grasp unknown components.

For practical validation of the findings, a robot cell with a collaborative robot from Universal Robots at the Technology Transfer Centre Nürnberger Land in Lauf is available.

## Requirements

- Programming skills (preferably Python and/or C++)
- Ideally initial experience with ROS and neural networks
- Interest in robotics and deep learning

This topic is suitable for a **bachelor's, project or master's thesis** and can also be combined with further topics for an **M-APR**.

## Supervision

| Role       | Name                         | E-Mail                              |
|------------|------------------------------|-------------------------------------|
| Supervisor | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de  |

**Location:** TTZ Nürnberger Land, Martin-Luther-Straße 18, Lauf an der Pegnitz

Further information: [TTZ Nürnberger Land](https://www.th-nuernberg.de/en/institutions/scientific-and-research-cooperations/technology-transfer-centre-nuernberger-land/) · [Mobile Robotics Lab](https://www.th-nuernberg.de/en/faculties/efi/research/research-active-laboratories/mobile-robotics/)
