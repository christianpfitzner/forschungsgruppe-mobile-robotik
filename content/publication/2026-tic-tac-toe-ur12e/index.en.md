---
title: 'Human-Robot Interaction on the UR12e – Tic-Tac-Toe as an Interactive Demo'

authors:
  - admin

date: '2026-06-12T00:00:00Z'
doi: ''
publishDate: '2026-06-12T00:00:00Z'

publication_types: ['thesis']

publication: "Project or Bachelor's Thesis, TH Nürnberg — TTZ Nürnberger Land"
publication_short: "TTZ Nürnberger Land"

abstract: |
  A UR12e robot arm from Universal Robots is available at the TTZ Nürnberger Land and is
  ideally suited for exploring and demonstrating human-robot interaction (HRI). The goal of
  this project thesis is to use this existing robot arm to realise a game-based interaction
  in which human and robot play Tic-Tac-Toe against each other.

  The robot is to capture the game state via a camera, compute its next move and place its
  pieces on the board autonomously and safely. The focus is on a robust interaction that is
  intuitive for non-experts: visitors should be able to play against the arm without any prior
  knowledge. The finished demo will then be used to present robotics in a tangible and
  approachable way at family events, open-house days or for visitor groups.

  On the software side, the work involves image processing to detect the board and the game
  pieces, a simple game logic (e.g. minimax) and control of the UR12e via its existing
  interfaces (e.g. ROS or URScript). Particular attention is paid to functional safety
  in collaborative operation, so that safe play right next to a person is possible.

  If the demo proves convincing, the system can be conceptually extended to more demanding
  games such as chess — involving more complex perception, grasping tasks and game logic. The
  thesis therefore also serves as a foundation for subsequent follow-up projects.

summary: 'Game-based human-robot interaction with the UR12e at TTZ Nürnberger Land: Tic-Tac-Toe with camera-based board detection, game logic and safe robot control as an approachable robotics demo — optionally extendable to chess.'

tags:
  - Robotics
  - Human-Robot Interaction
  - UR12e
  - Universal Robots
  - Cobot
  - Computer Vision
  - ROS
  - Tic-Tac-Toe
  - Chess
  - TTZ Nürnberger Land
  - Demonstrator
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
  caption: 'UR robot arm playing against a human — Tic-Tac-Toe today, chess as an outlook'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Motivation

Collaborative robot arms such as the UR12e make robotics immediately tangible — especially when
people can interact with them directly. A game like Tic-Tac-Toe is ideal for this: everyone knows
the rules, the outcome is easy to follow, and the robot demonstrates perception, decision-making
and precise motion in a single, illustrative sequence.

At the TTZ Nürnberger Land, this is to become the basis for a demonstrator that makes robotics
graspable for a broad audience — at family events, open-house days and for visitor groups. At the
same time, the project serves as a platform to put concepts of safe human-robot interaction into
practice.

## Work Packages

**Perception**
- Camera-based detection of the board and the placed game pieces
- Calibration between camera and robot coordinate frames (hand-eye calibration)

**Game Logic**
- Implementation of the Tic-Tac-Toe logic (e.g. minimax) for move computation
- Detection of game end, win, loss and draw

**Robot Control**
- Control of the UR12e via its existing interfaces (ROS or URScript)
- Grasping and safely placing the game pieces
- Functional safety in collaborative operation (force/speed limiting)

**Interaction & Demo**
- Intuitive game flow and user guidance understandable for non-experts
- Robustness testing and preparation as a presentable demo
- Optional outlook: conceptual extension to chess

## Requirements

- Programming skills in Python and/or C++
- Ideally some prior exposure to robotics
- Interest in computer vision, game logic and human-robot interaction
- Enthusiasm for hands-on work with real robot hardware

This topic is offered as a **project or bachelor's thesis** and, given a good fit, can serve as
a foundation for follow-up work (e.g. extension to chess).

## Supervision

| Role          | Name                         | E-Mail                                 |
|---------------|------------------------------|----------------------------------------|
| Supervisor    | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
| Co-Supervisor | M. Sc. Patrick Fußy          | patrick.fussy@th-nuernberg.de         |

**Location:** TTZ Nürnberger Land / TH Nürnberg Georg Simon Ohm
