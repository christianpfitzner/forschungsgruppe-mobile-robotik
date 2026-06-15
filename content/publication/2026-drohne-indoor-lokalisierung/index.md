---
title: 'Markerlose Indoor-Lokalisierung einer Drohne ohne GNSS'

authors:
  - admin

date: '2026-06-15T00:00:00Z'
doi: ''
publishDate: '2026-06-15T00:00:00Z'

publication_types: ['thesis']

publication: "Projekt- oder Bachelorarbeit, TH Nürnberg — Labor für mobile Robotik, AerodrOHM"
publication_short: "Labor für mobile Robotik"

abstract: |
  Die im AerodrOHM eingesetzte Drohne bestimmt ihre Position bisher über ein externes,
  markerbasiertes Trackingsystem. Dieses liefert zwar sehr genaue Posen, setzt aber einen
  fest installierten, instrumentierten Flugraum voraus und ist außerhalb dieses Raums nicht
  verfügbar. Ziel dieser Arbeit ist es, die bestehende Drohne in die Lage zu versetzen, sich
  im Innenraum ohne GNSS und ohne Marker allein anhand ihrer Onboard-Sensorik selbst zu
  lokalisieren.

  Die Arbeit baut unmittelbar auf der vorhandenen Drohne und der bestehenden ROS-basierten
  Systemarchitektur auf. Im ersten Schritt wird geeignete Onboard-Sensorik (Kamera, IMU,
  optional Optical-Flow- oder Tiefensensor) ausgewählt und integriert. Darauf aufbauend wird
  ein markerloses Lokalisierungsverfahren umgesetzt, beispielsweise eine Visual-Inertial
  Odometry (VIO) oder ein Visual-SLAM-Ansatz, das die Eigenbewegung der Drohne kontinuierlich
  schätzt und in die Flugregelung einspeist.

  Abschließend wird die erreichte Genauigkeit und Robustheit systematisch bewertet. Als
  Referenz (Ground Truth) dient das vorhandene markerbasierte Trackingsystem im AerodrOHM,
  gegen das die markerlose Lösung in Flugversuchen verglichen wird.

summary: 'Die im AerodrOHM eingesetzte Drohne lokalisiert sich bisher über externe Marker. Ziel ist eine markerlose, GNSS-freie Indoor-Lokalisierung allein mit Onboard-Sensorik (Visual-Inertial Odometry / SLAM), aufbauend auf der bestehenden Plattform.'

tags:
  - Drohnen
  - Indoor-Lokalisierung
  - GNSS-frei
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
  caption: 'Drohne im Flugraum des AerodrOHM'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Beschreibung

Die im AerodrOHM eingesetzte Drohne bestimmt ihre Position bisher über ein externes,
markerbasiertes Trackingsystem. Dieses liefert sehr genaue Posen, setzt jedoch einen fest
installierten, instrumentierten Flugraum voraus. Ziel dieser Arbeit ist eine markerlose,
GNSS-freie Indoor-Lokalisierung allein auf Basis der Onboard-Sensorik, sodass die Drohne
unabhängig vom externen Tracking fliegen kann. Die Arbeit baut auf der vorhandenen Drohne und
der bestehenden ROS-Systemarchitektur auf.

## Arbeitspakete

- Einarbeitung in die bestehende Drohnen-Plattform und das markerbasierte Trackingsystem im AerodrOHM
- Auswahl und Integration geeigneter Onboard-Sensorik (Kamera, IMU, ggf. Optical-Flow- oder Tiefensensor)
- Implementierung eines markerlosen, GNSS-freien Lokalisierungsverfahrens (z. B. Visual-Inertial Odometry oder Visual SLAM)
- Integration in die bestehende ROS-Systemarchitektur und Flugregelung
- Evaluation der Genauigkeit und Robustheit gegen das markerbasierte Tracking als Ground Truth
- Flugversuche und Dokumentation der Ergebnisse im AerodrOHM

## Voraussetzungen

- Kenntnisse in Programmierung (Python und/oder C++)
- Idealerweise erste Erfahrungen mit ROS / ROS 2
- Grundkenntnisse in Computer Vision und/oder Zustandsschätzung (z. B. Kalman-Filter)
- Interesse an Drohnen, Sensorintegration und Lokalisierung
- Selbstständige und sorgfältige Arbeitsweise

Das Thema kann nach Abstimmung als **Projekt- oder Bachelorarbeit** bearbeitet werden.

## Betreuung

| Rolle    | Name                         | E-Mail                                 |
|----------|------------------------------|----------------------------------------|
| Betreuer | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
