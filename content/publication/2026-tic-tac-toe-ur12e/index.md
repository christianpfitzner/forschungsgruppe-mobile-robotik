---
title: 'Mensch-Roboter-Interaktion am UR12e – Tic-Tac-Toe als interaktive Demo'

authors:
  - admin

date: '2026-06-12T00:00:00Z'
doi: ''
publishDate: '2026-06-12T00:00:00Z'

publication_types: ['thesis']

publication: "Projekt- oder Bachelorarbeit, TH Nürnberg — TTZ Nürnberger Land"
publication_short: "TTZ Nürnberger Land"

abstract: |
  Am TTZ Nürnberger Land steht ein UR12e-Roboterarm von Universal Robots zur Verfügung,
  der sich hervorragend für die Erforschung und Demonstration von Mensch-Roboter-Interaktion
  (MRI) eignet. Ziel dieser Projektarbeit ist es, mit diesem bestehenden Roboterarm eine
  spielbasierte Interaktion zu realisieren, bei der Mensch und Roboter gegeneinander
  Tic-Tac-Toe spielen.

  Der Roboter soll dabei den Spielzustand über eine Kamera erfassen, den nächsten Zug
  berechnen und seine Spielsteine eigenständig und sicher auf dem Spielfeld platzieren.
  Im Vordergrund steht eine robuste und für Laien intuitive Interaktion: Besucherinnen und
  Besucher sollen ohne Vorkenntnisse gegen den Arm antreten können. Die fertige Demo wird
  anschließend genutzt, um das Thema Robotik bei Familienfesten, Tagen der offenen Tür oder
  bei Besuchergruppen anschaulich und greifbar zu präsentieren.

  Auf der Softwareseite sind die Bildverarbeitung zur Erkennung des Spielfeldes und der
  Spielsteine, eine einfache Spiellogik (z. B. Minimax) sowie die Ansteuerung des UR12e
  über die vorhandenen Schnittstellen (z. B. ROS oder URScript) zu implementieren.
  Besonderes Augenmerk gilt der funktionalen Sicherheit im kollaborativen Betrieb, damit
  ein gefahrloses Spielen direkt neben dem Menschen möglich ist.

  Läuft die Demo überzeugend, kann das System konzeptionell auf anspruchsvollere Spiele wie
  Schach erweitert werden — mit komplexerer Wahrnehmung, Greifaufgaben und Spiellogik. Die
  Arbeit eignet sich damit auch als Grundlage für aufbauende Folgeprojekte.

summary: 'Spielbasierte Mensch-Roboter-Interaktion mit dem UR12e am TTZ Nürnberger Land: Tic-Tac-Toe mit kamerabasierter Spielfelderkennung, Spiellogik und sicherer Roboteransteuerung als anschauliche Robotik-Demo — optional erweiterbar auf Schach.'

tags:
  - Robotik
  - Mensch-Roboter-Interaktion
  - UR12e
  - Universal Robots
  - Cobot
  - Bildverarbeitung
  - ROS
  - Tic-Tac-Toe
  - Schach
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
  caption: 'UR-Roboterarm beim Spiel gegen den Menschen — Tic-Tac-Toe heute, Schach als Ausblick'
  focal_point: 'Smart'
  preview_only: false

projects: []
slides: ''
---

## Motivation

Kollaborative Roboterarme wie der UR12e machen Robotik unmittelbar erlebbar — besonders dann,
wenn Menschen direkt mit ihnen interagieren können. Ein Spiel wie Tic-Tac-Toe ist dafür ideal:
Die Regeln kennt jeder, der Spielausgang ist nachvollziehbar, und der Roboter zeigt Wahrnehmung,
Entscheidungsfindung und präzise Bewegung in einem einzigen, anschaulichen Ablauf.

Am TTZ Nürnberger Land soll auf dieser Basis ein Demonstrator entstehen, der das Thema Robotik
für ein breites Publikum greifbar macht — bei Familienfesten, Tagen der offenen Tür und
Besuchergruppen. Gleichzeitig dient das Projekt als Plattform, um Konzepte der sicheren
Mensch-Roboter-Interaktion praktisch zu erproben.

## Arbeitspakete

**Wahrnehmung**
- Kamerabasierte Erkennung des Spielfeldes und der gesetzten Spielsteine
- Kalibrierung zwischen Kamera- und Roboterkoordinatensystem (Hand-Auge-Kalibrierung)

**Spiellogik**
- Implementierung der Tic-Tac-Toe-Logik (z. B. Minimax) zur Zugberechnung
- Erkennung von Spielende, Sieg, Niederlage und Unentschieden

**Roboteransteuerung**
- Ansteuerung des UR12e über vorhandene Schnittstellen (ROS oder URScript)
- Greifen und sicheres Platzieren der Spielsteine
- Funktionale Sicherheit im kollaborativen Betrieb (Kraft-/Geschwindigkeitsbegrenzung)

**Interaktion & Demo**
- Intuitive, für Laien verständliche Spielführung und Nutzerführung
- Robustheitstests und Aufbereitung als vorführbare Demo
- Optionaler Ausblick: konzeptionelle Erweiterung auf Schach

## Voraussetzungen

- Programmierkenntnisse in Python und/oder C++
- Idealerweise erste Berührungspunkte zur Robotik
- Interesse an Bildverarbeitung, Spiellogik und Mensch-Roboter-Interaktion
- Freude an praktischer Arbeit mit realer Roboterhardware

Das Thema wird als **Projekt- oder Bachelorarbeit** ausgeschrieben und kann bei guter Eignung
als Grundlage für aufbauende Arbeiten (z. B. Erweiterung auf Schach) dienen.

## Betreuung

| Rolle       | Name                         | E-Mail                                 |
|-------------|------------------------------|----------------------------------------|
| Betreuer    | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
| Co-Betreuer | M. Sc. Patrick Fußy          | patrick.fussy@th-nuernberg.de         |

**Ort:** TTZ Nürnberger Land / TH Nürnberg Georg Simon Ohm
