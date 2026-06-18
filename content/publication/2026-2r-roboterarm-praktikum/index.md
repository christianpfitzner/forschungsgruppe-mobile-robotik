---
title: '2R-Roboterarm als Praktikumsversuch – Gravity Compensation und Reinforcement Learning'

authors:
  - admin

date: '2026-06-08T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']
status: 'offen'

publication: "Projekt- oder Masterarbeit, TH Nürnberg — Labor für mobile Robotik"
publication_short: "Labor für mobile Robotik"

abstract: |
  Im Masterstudiengang M-IAS (Intelligent Autonomous Systems) an der TH Nürnberg wird im
  Rahmen des Praktikums "Intelligent Robotics" ein neuer Versuchsaufbau benötigt, der
  grundlegende Konzepte der Regelungstechnik und des maschinellen Lernens anschaulich
  demonstriert. Ziel dieser Arbeit ist der Aufbau eines zweiachsigen Roboterarms (2R-Kinematik),
  der auf zwei BLDC-Motoren basiert und als vielseitige Demonstrationsplattform für
  Gravity Compensation und Reinforcement Learning dient.

  Auf der Hardwareseite sind die beiden Gelenke mit BLDC-Motoren und geeigneten
  Motortreibern (z. B. ODrive oder VESC) auszustatten. Die mechanische Struktur der
  Armsegmente ist zu entwerfen und zu fertigen, wobei Aspekte wie Steifigkeit, Gewicht
  und Zugänglichkeit für die Studierenden zu berücksichtigen sind. Encoder liefern die
  notwendige Positions- und Geschwindigkeitsrückmeldung für die Regelung.

  Softwareseitig sind zunächst Vorwärts- und Rückwärtskinematik zu implementieren sowie
  eine modellbasierte Gravity-Compensation, die das Eigengewicht der Armsegmente in
  Echtzeit kompensiert und den Arm in beliebigen Positionen schwebend hält. Dieses
  physikalisch anschauliche Experiment bildet den Einstieg für Studierende in die
  modellbasierte Regelung.

  Darauf aufbauend soll ein Reinforcement-Learning-Demo entstehen, bei dem ein Agent
  den Arm auf eine Zielposition einlernt. Dabei ist eine ROS-basierte Systemarchitektur
  zu etablieren, die sowohl die reale Hardware als auch eine Simulationsumgebung
  (z. B. Gazebo oder MuJoCo) für das RL-Training unterstützt. Abschließend sind
  Versuchsanleitungen zu erstellen, die den Praktikumseinsatz für Studierende ermöglichen.

summary: 'Aufbau eines 2R-Roboterarms mit BLDC-Motoren als Praktikumsversuch für M-IAS: modellbasierte Gravity Compensation und Reinforcement-Learning-Demo mit ROS-Integration und Simulationsanbindung.'

tags:
  - Robotik
  - BLDC
  - Gravity Compensation
  - Reinforcement Learning
  - ROS
  - Kinematik
  - Regelungstechnik
  - M-IAS
  - Praktikum
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

Im Praktikum "Intelligent Robotics" des Masterstudiengangs M-IAS fehlt bislang ein
hands-on Versuch, der die Brücke zwischen klassischer modellbasierter Regelung und
modernen lernbasierten Methoden schlägt. Ein 2R-Roboterarm mit Drehmomentsteuerung
bietet genau diese Möglichkeit: Studierende erleben zunächst die physikalischen Effekte
der Schwerkraft am realen System und lernen anschließend, wie ein RL-Agent dieselbe
Aufgabe datengetrieben löst.

## Arbeitspakete

**Hardware**
- Auswahl und Inbetriebnahme der BLDC-Motoren und Motortreiber (z. B. ODrive / VESC)
- Mechanischer Entwurf und Fertigung der Armsegmente (CAD, 3D-Druck oder Aluminiumprofil)
- Integration von Encodern und Verkabelung

**Software & Regelung**
- Implementierung von Vorwärts- und Rückwärtskinematik
- Modellbasierte Gravity-Compensation-Regelung (Drehmomentkompensation in Echtzeit)
- ROS-Integration: Topics, Services und ggf. ros2_control

**Reinforcement Learning**
- Aufbau einer Simulationsumgebung (Gazebo oder MuJoCo) für das RL-Training
- Training eines Agenten (z. B. PPO / SAC) auf eine Zielpositions-Aufgabe
- Sim-to-Real-Transfer und Evaluation am realen Arm

**Dokumentation**
- Erstellung von Versuchsanleitungen für den Praktikumseinsatz im M-IAS-Studiengang

## Voraussetzungen

- Kenntnisse in Regelungstechnik und Robotik (Kinematik, Dynamik)
- Programmierkenntnisse in Python und/oder C++
- Idealerweise Erfahrung mit ROS
- Interesse an maschinellem Lernen und Reinforcement Learning
- Freude an praktischem Hardware-Aufbau und Prototyping

Das Thema kann nach Abstimmung als **Projekt- oder Masterarbeit** bearbeitet werden.

## Betreuung

| Rolle    | Name                         | E-Mail                                 |
|----------|------------------------------|----------------------------------------|
| Betreuer | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
