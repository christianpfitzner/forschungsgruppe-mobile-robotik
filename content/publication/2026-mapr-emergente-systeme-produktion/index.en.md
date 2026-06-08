---
title: 'Emergent Systems in Production'

authors:
  - admin

date: '2026-06-09T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']

publication: "M-APR (3 semesters), from WiSe 2026/2027 — TTZ Nürnberger Land / TH Nürnberg"
publication_short: "TTZ Nürnberger Land"

abstract: |
  Modern production environments increasingly rely on heterogeneous robot fleets — autonomous
  mobile robots (AMR), collaborative robot arms and stationary processing stations — that
  jointly handle manufacturing and logistics tasks. Today, coordination of these systems is
  predominantly centralised via supervisory computers or Manufacturing Execution Systems.
  However, centralised coordination is vulnerable to disruptions, machine failures or
  short-notice order changes: if the central node fails, the entire process chain comes to a halt.

  This M-APR project investigates whether and under what conditions decentralised, emergent
  coordination strategies — where agents autonomously take on roles and distribute tasks based
  on local information — outperform centralised control in production scenarios. The focus is
  on the systematic comparison of centralised and decentralised approaches under controlled
  variations of adversarial conditions (communication failures, machine failures, dynamic order changes).

summary: 'Comparison of centralised and decentralised (emergent) coordination strategies for heterogeneous robot fleets in production environments. Simulation in ROS 2 / Gazebo, multi-agent reinforcement learning, validation on real hardware at TTZ.'

tags:
  - Multi-Agent Systems
  - Production Robotics
  - Reinforcement Learning
  - ROS 2
  - Gazebo
  - Emergence
  - AMR
  - TTZ Nürnberger Land
  - M-APR
  - Masterarbeit
  - Projektarbeit

categories:
  - M-APR
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

## Project Description

This 3-semester M-APR project (starting WiSe 2026/2027) compares centralised and decentralised
coordination strategies for heterogeneous robot fleets in simulated and real production scenarios.
The scientific contribution lies in the empirical characterisation of the transition between
both coordination paradigms under varied adversarial conditions.

## Structure over Three Semesters

**Semester 1 — Foundations and Simulation**
- Literature review on decentralised coordination and multi-agent reinforcement learning
- Building the ROS 2-based simulation environment (at least two agent types: mobile and stationary)
- Implementation of a centralised baseline and a simple decentralised approach

**Semester 2 — Comparative Study and Learning-Based Coordination**
- Implementation of learning-based decentralised coordination (MARL)
- Systematic comparison under varied adversarial conditions (communication failure, machine failure, dynamic order changes)
- Statistical evaluation and identification of transition points between coordination regimes

**Semester 3 — Validation and Publication**
- Transfer of selected scenarios to real hardware at TTZ
- Evaluation of sim-to-real transferability
- Completion of master's thesis and preparation of a conference publication (MAPR conference)

## Requirements

- Bachelor's degree in electrical engineering, computer science, mechatronics, robotics or equivalent
- Programming in C++ and/or Python
- Basic knowledge of machine learning / reinforcement learning
- Experience with ROS 2 and simulation (Gazebo or similar) is an advantage
- Interest in multi-agent systems and production robotics

This topic can also be completed as a **project or master's thesis** subject to agreement.

## Supervision

| | |
|---|---|
| **Prof. Dr. Christian Pfitzner** | [christian.pfitzner@th-nuernberg.de](mailto:christian.pfitzner@th-nuernberg.de) |
| **Waldemar Haag** | [waldemar.haag@th-nuernberg.de](mailto:waldemar.haag@th-nuernberg.de) |

**Location:** TTZ Nürnberger Land, Lauf an der Pegnitz

Further information: [TTZ Nürnberger Land](https://www.th-nuernberg.de/einrichtungen-gesamt/wissenschaftliche-und-forschungskooperationen/technologietransferzentrum-nuernberger-land/) · [Mobile Robotics Lab](https://www.th-nuernberg.de/fakultaeten/efi/forschung/forschungsaktive-labore/mobile-robotik/)
