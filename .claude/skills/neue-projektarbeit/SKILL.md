---
name: neue-projektarbeit
description: >-
  Legt eine neue ausgeschriebene wissenschaftliche Arbeit (Projektarbeit,
  Bachelorarbeit, Masterarbeit oder M-APR) für die Website der Forschungsgruppe
  Mobile Robotik an. Verwenden, wenn der Nutzer eine neue Arbeit / ein neues
  Thema / eine Ausschreibung anlegen, hinzufügen oder ausschreiben möchte
  (z. B. "neue Projektarbeit", "Bachelorarbeit ausschreiben", "Thema anlegen").
  Erzeugt den Ordner unter content/publication/ mit deutscher (index.md) und
  englischer (index.en.md) Fassung im korrekten Hugo-Wowchemy-Format.
---

# Neue ausgeschriebene Arbeit anlegen

Dieser Skill erstellt eine neue Ausschreibung im Verzeichnis
`content/publication/`. Jede Arbeit besteht aus **einem Ordner** mit **zwei
Dateien**: `index.md` (Deutsch) und `index.en.md` (Englisch). Beide MÜSSEN
inhaltlich identische Aussagen treffen – nur die Sprache unterscheidet sich.

## Ablauf

1. **Informationen sammeln.** Wenn nicht vom Nutzer angegeben, kurz nachfragen
   nach: Titel/Thema, Art der Arbeit (Projektarbeit / Bachelorarbeit /
   Masterarbeit / M-APR – auch Kombinationen möglich), Kurzbeschreibung der
   Aufgabe, Standort/Labor (Labor für mobile Robotik, TTZ Nürnberger Land …)
   und ggf. ein abweichender Betreuer. Fehlt nur Detailtiefe, sinnvoll aus dem
   Thema ableiten statt jede Kleinigkeit zu erfragen.

2. **Ordnernamen (Slug) bilden.** Schema: `content/publication/<YYYY>-<slug>/`
   – das aktuelle Jahr, dann ein kurzer, sprechender Bindestrich-Slug in
   Kleinbuchstaben, nur `a–z`, `0–9` und `-` (keine Umlaute: ä→ae, ö→oe,
   ü→ue, ß→ss). Optional darf der Monat ergänzt werden:
   `<YYYY>-<MM>-<slug>` (so wie bei `2026-06-mini-roboter-mecanum`).
   Beispiele: `2026-2r-roboterarm-praktikum`, `2026-drone-light-painting`.
   Vor dem Anlegen prüfen, dass der Ordner noch nicht existiert.

3. **Beide Dateien erzeugen** nach den Vorlagen unten. `date` und
   `publishDate` auf das heutige Datum im Format `YYYY-MM-DDT00:00:00Z`
   setzen.

4. **Konsistenz prüfen:** `tags` und `categories` müssen in DE und EN
   identisch sein (Tags/Kategorien werden NICHT übersetzt – siehe Regeln).
   Der Slug-Ordner ist für beide Sprachen derselbe.

5. **Dem Nutzer den Ordnerpfad nennen** und fragen, ob committet/gepusht
   werden soll (sofern nicht ohnehin schon beauftragt).

## Feste Regeln

- `publication_types` ist **immer** `['thesis']`.
- `authors` ist **immer** `- admin` (Prof. Dr. Christian Pfitzner), außer der
  Nutzer nennt explizit andere Autoren.
- `categories` und die Kategorie-Tags sind **deutschsprachig und werden auch
  in der englischen Datei NICHT übersetzt**. Erlaubte Werte:
  `Projektarbeit`, `Bachelorarbeit`, `Masterarbeit`, `M-APR`.
  Es können mehrere kombiniert werden (z. B. eine Arbeit, die als Projekt-
  oder Masterarbeit vergeben werden kann → beide Kategorien).
- Die Kategorie-Namen müssen exakt den `tag`-Werten in
  `content/publication/_index.md` entsprechen, damit die Filter-Buttons auf
  der Website greifen. Diese Datei NICHT verändern, es sei denn, es soll eine
  neue Kategorie eingeführt werden.
- Am Ende der `tags`-Liste die zutreffenden Arbeits-Kategorien
  (z. B. `Masterarbeit`, `Projektarbeit`) mit aufnehmen – ebenfalls
  unübersetzt in beiden Sprachen.
- `featured: true` setzen, damit die Arbeit prominent erscheint.
- Standard-Betreuer (sofern nichts anderes genannt):
  Prof. Dr. Christian Pfitzner, christian.pfitzner@th-nuernberg.de.
- Die englische Datei spiegelt die deutsche 1:1: gleiche Struktur, gleiche
  Arbeitspakete, gleiche Voraussetzungen – nur übersetzt.

## Vorlage `index.md` (Deutsch)

```markdown
---
title: '<Deutscher Titel der Arbeit>'

authors:
  - admin

date: '<YYYY-MM-DD>T00:00:00Z'
doi: ''
publishDate: '<YYYY-MM-DD>T00:00:00Z'

publication_types: ['thesis']

publication: "<z. B. Projekt- oder Masterarbeit, TH Nürnberg — Labor für mobile Robotik>"
publication_short: "<z. B. Labor für mobile Robotik>"

abstract: |
  <Mehrere Absätze, die Kontext, Aufgabenstellung und Ziel der Arbeit
  beschreiben. Pro Absatz eine Leerzeile. Einrückung mit zwei Leerzeichen
  beibehalten.>

summary: '<Ein bis zwei Sätze Kurzfassung für die Kartenansicht.>'

tags:
  - <Fachthema 1>
  - <Fachthema 2>
  - <…>
  - <zutreffende Kategorie(n), z. B. Masterarbeit>
  - <z. B. Projektarbeit>

categories:
  - <z. B. Masterarbeit>
  - <z. B. Projektarbeit>

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

<Warum ist diese Arbeit interessant/relevant? 1–2 Absätze.>

## Arbeitspakete

**<Themenblock 1, z. B. Hardware>**
- <Aufgabe>
- <Aufgabe>

**<Themenblock 2, z. B. Software & Regelung>**
- <Aufgabe>
- <Aufgabe>

**Dokumentation**
- <Aufgabe>

## Voraussetzungen

- <Voraussetzung 1>
- <Voraussetzung 2>
- <…>

Das Thema kann nach Abstimmung als **<Projekt-/Bachelor-/Masterarbeit>**
bearbeitet werden.

## Betreuung

| Rolle    | Name                         | E-Mail                              |
|----------|------------------------------|-------------------------------------|
| Betreuer | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de  |
```

## Vorlage `index.en.md` (Englisch)

```markdown
---
title: '<English title of the thesis>'

authors:
  - admin

date: '<YYYY-MM-DD>T00:00:00Z'
doi: ''
publishDate: '<YYYY-MM-DD>T00:00:00Z'

publication_types: ['thesis']

publication: "<e.g. Project or Master's Thesis, TH Nürnberg — Mobile Robotics Lab>"
publication_short: "<e.g. Mobile Robotics Lab>"

abstract: |
  <Same content as the German abstract, translated into English. Keep the
  paragraph structure and the two-space indentation.>

summary: '<One or two sentence summary, English translation of the German one.>'

tags:
  - <Topic 1 in English>
  - <Topic 2 in English>
  - <…>
  - <category tag(s), kept in German, e.g. Masterarbeit>
  - <e.g. Projektarbeit>

categories:
  - <e.g. Masterarbeit>
  - <e.g. Projektarbeit>

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

<English translation of the motivation.>

## Work Packages

**<Topic block 1, e.g. Hardware>**
- <Task>
- <Task>

**<Topic block 2, e.g. Software & Control>**
- <Task>
- <Task>

**Documentation**
- <Task>

## Requirements

- <Requirement 1>
- <Requirement 2>
- <…>

This topic can be completed as a **<project/bachelor's/master's thesis>**
subject to agreement.

## Supervision

| Role       | Name                         | E-Mail                              |
|------------|------------------------------|-------------------------------------|
| Supervisor | Prof. Dr. Christian Pfitzner | christian.pfitzner@th-nuernberg.de  |
```

## Hinweise

- `categories` steuern die Filter-Buttons unter „Ausgeschriebene Arbeiten".
  Sind die Werte falsch geschrieben, erscheint die Arbeit nicht im Filter.
- Die Kategorie `M-APR` bezeichnet Arbeiten im Modul „Angewandte
  Projektarbeit" und wird wie eine eigene Art behandelt.
- Bei mehreren möglichen Arbeitsformen alle relevanten Kategorien angeben,
  damit die Ausschreibung in jedem passenden Filter auftaucht.
- Reale Referenzbeispiele zum Abgleich im Repo:
  `content/publication/2026-2r-roboterarm-praktikum/` (Projekt-/Masterarbeit),
  `content/publication/2026-fallstudie-technologien-kmu/` (reine Projektarbeit),
  `content/publication/2026-drone-light-painting/` (Projekt-/Bachelor-/Masterarbeit).
