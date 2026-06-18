---
title: 'Emergente Systeme in der Produktion'

authors:
  - admin

date: '2026-06-09T00:00:00Z'
doi: ''
publishDate: '2026-06-08T00:00:00Z'

publication_types: ['thesis']
status: 'offen'

publication: "M-APR (3 Semester), ab WiSe 2026/2027 — TTZ Nürnberger Land / TH Nürnberg"
publication_short: "TTZ Nürnberger Land"

abstract: |
  Moderne Produktionsumgebungen setzen zunehmend auf heterogene Roboterflotten — mobile
  Transportplattformen (AMR), kollaborative Roboterarme und stationäre Bearbeitungsstationen —,
  die gemeinsam Fertigungs- und Logistikaufgaben bewältigen. Die Koordination dieser Systeme
  erfolgt heute überwiegend zentral über Leitrechner oder Manufacturing Execution Systems.
  Bei Störungen, Maschinenausfällen oder kurzfristigen Auftragswechseln ist eine zentrale
  Koordination jedoch anfällig: Fällt der zentrale Knoten aus, steht die gesamte Prozesskette still.

  Das M-APR-Projekt untersucht, ob und unter welchen Bedingungen dezentrale, emergente
  Koordinationsstrategien — bei denen Agenten autonom auf Basis lokaler Information Rollen
  übernehmen und Aufgaben verteilen — einer zentralen Steuerung in Produktionsszenarien
  überlegen sind. Im Fokus steht der systematische Vergleich zentraler und dezentraler
  Ansätze unter kontrolliert variierten Störbedingungen (Kommunikationsausfälle,
  Maschinenausfälle, dynamische Auftragslage).

summary: 'Vergleich zentraler und dezentraler (emergenter) Koordinationsstrategien für heterogene Roboterflotten in Produktionsumgebungen. Simulation in ROS 2 / Gazebo, Multi-Agent Reinforcement Learning, Validierung an realer Hardware am TTZ.'

tags:
  - Multi-Agent Systeme
  - Produktionsrobotik
  - Reinforcement Learning
  - ROS 2
  - Gazebo
  - Emergenz
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

## Projektbeschreibung

Das M-APR-Projekt (3 Semester, Start WiSe 2026/2027) vergleicht zentrale und dezentrale
Koordinationsstrategien für heterogene Roboterflotten in simulierten und realen
Produktionsszenarien. Der wissenschaftliche Beitrag liegt in der empirischen Charakterisierung
des Übergangs zwischen beiden Koordinationsformen unter variierten Adversitätsbedingungen.

## Grobstruktur über drei Semester

**Semester 1 — Grundlagen und Simulation**
- Literaturrecherche zu dezentraler Koordination und Multi-Agent Reinforcement Learning
- Aufbau der ROS-2-basierten Simulationsumgebung (mind. zwei Agententypen: mobil und stationär)
- Implementierung einer zentralen Baseline und eines einfachen dezentralen Verfahrens

**Semester 2 — Vergleichsstudie und lernbasierte Koordination**
- Implementierung lernbasierter dezentraler Koordination (MARL)
- Systematischer Vergleich unter variierten Störbedingungen (Kommunikationsausfall, Maschinenausfall, dynamische Auftragswechsel)
- Statistische Auswertung und Identifikation von Übergangspunkten

**Semester 3 — Validierung und Publikation**
- Transfer ausgewählter Szenarien auf reale Hardware am TTZ
- Auswertung der Sim-to-Real-Übertragbarkeit
- Anfertigung der Masterarbeit und Vorbereitung einer Konferenzpublikation (MAPR-Konferenz)

## Voraussetzungen

- Bachelorabschluss in Elektro- und Informationstechnik, Informatik, Mechatronik, Robotik o. ä.
- Programmierung in C++ und/oder Python
- Grundkenntnisse in Machine Learning / Reinforcement Learning
- Erfahrung mit ROS 2 und Simulation (Gazebo o. ä.) von Vorteil
- Interesse an Multi-Agenten-Systemen und Produktionsrobotik

Das Thema kann nach Abstimmung auch als **Projekt- oder Masterarbeit** bearbeitet werden.

## Betreuung

| Rolle       | Name                         | E-Mail                                 |
|-------------|------------------------------|----------------------------------------|
| Betreuer    | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de    |
| Co-Betreuer | Waldemar Haag                | waldemar.haag@th-nuernberg.de         |

**Ort:** TTZ Nürnberger Land, Lauf an der Pegnitz

Weitere Informationen: [TTZ Nürnberger Land](https://www.th-nuernberg.de/einrichtungen-gesamt/wissenschaftliche-und-forschungskooperationen/technologietransferzentrum-nuernberger-land/) · [Labor für Mobile Robotik](https://www.th-nuernberg.de/fakultaeten/efi/forschung/forschungsaktive-labore/mobile-robotik/)
