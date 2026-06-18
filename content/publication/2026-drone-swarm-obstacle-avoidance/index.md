---
title: 'Drone Swarm Obstacle Avoidance – Kollisionsfreie Navigation von Micro-Drohnen'

authors:
  - admin

date: '2026-06-08T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']
status: 'offen'

publication: "Projekt- oder Masterarbeit, TH Nürnberg — Labor für mobile Robotik, AerodrOHM"
publication_short: "Labor für mobile Robotik"

abstract: |
  Die am AerodrOHM eingesetzten Micro-Drohnen (Crazyflies) verfügen über keine ausgeprägte
  Onboard-Sensorik zur Umgebungswahrnehmung. Um dennoch eine sichere Interaktion mit Personen
  im Flugraum zu ermöglichen, soll eine externe 3D-Kamera in der Nähe des Schwarms installiert
  werden. Das Ziel ist ein System, das Personen im gemeinsamen Flugraum zuverlässig erkennt
  und den Schwarm so steuert, dass die Drohnen automatisch ausweichen und Raum freigeben.

  Im ersten Schritt soll die 3D-Kamera in eine ROS-basierte Systemarchitektur eingebunden
  werden. Die gewonnenen Punktwolkendaten müssen gefiltert, vorverarbeitet und in ein geeignetes
  Koordinatensystem transformiert werden. Ein zentraler Aspekt ist die Klassifikation der
  erfassten Objekte: Das System muss zuverlässig zwischen Personen und den Drohnen selbst
  unterscheiden können. Hierfür kommen Verfahren der Segmentierung und Objekterkennung auf
  3D-Daten in Frage, etwa clusterbasierte Ansätze oder lernende Verfahren.

  Aufbauend auf der Personenerkennung soll ein reaktives Schwarmverhalten entwickelt werden,
  das eine sichere Koexistenz im gemeinsamen Raum gewährleistet. Dazu gehört die Definition
  von Sicherheitszonen um erkannte Personen, die dynamische Anpassung der Flugbahnen sowie
  die Koordination der Ausweichmanöver innerhalb des Schwarms, sodass auch Kollisionen zwischen
  den Drohnen vermieden werden. Die praktische Erprobung findet im Flugraum des AerodrOHM statt.

summary: 'Entwicklung eines Systems zur kollisionsfreien Navigation von Crazyflie-Drohnenschwärmen mittels externer 3D-Kamera, ROS-Integration und reaktivem Schwarmverhalten. Erprobung im Flugraum des AerodrOHM.'

tags:
  - Drohnen
  - Schwarmrobotik
  - ROS
  - Punktwolken
  - Personenerkennung
  - Hindernisvermeidung
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
  caption: 'Crazyflie Micro-Drohnen im AerodrOHM'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Arbeitspakete

- Einbindung und Kalibrierung der externen 3D-Kamera
- Verarbeitung, Filterung und Transformation der Punktwolkendaten
- Entwicklung einer Klassifikation zur Unterscheidung von Personen und Drohnen
- Entwurf und Implementierung eines reaktiven Schwarmverhaltens mit Sicherheitszonen
- Test und Evaluation im Flugraum mit realen Personen

## Voraussetzungen

- Kenntnisse in Programmierung (Python und/oder C++)
- Idealerweise erste Erfahrungen mit ROS
- Interesse an Sensorintegration, Punktwolkenverarbeitung und Wahrnehmungsverfahren

Das Thema kann nach Abstimmung als **Projekt- oder Masterarbeit** bearbeitet werden.

## Betreuung

| Rolle    | Name                         | E-Mail                                 |
|----------|------------------------------|----------------------------------------|
| Betreuer | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
