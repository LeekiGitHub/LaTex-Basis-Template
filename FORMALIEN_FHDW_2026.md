# FHDW-Formalienabgleich (Stand 2026)

Quelle: `FHDW-NRW_Formalien_Wissenschaftliche_Arbeiten.pdf` (gueltig ab 01.01.2026)

## Kurzfazit

- **Abgedeckt im Template:** Titelblatt, Inhaltsverzeichnis, Abbildungs-/Tabellenverzeichnis, Textteil, Quellenverzeichnis, Ehrenwoertliche Erklaerung, Anhang inkl. KI-Dokumentation.
- **Neu/aktualisiert:** FHDW-konforme Seitenraender, Times-basierte 12pt Schrift, optionale Executive Summary, separates Anhangsverzeichnis, auslagerte KI-Nutzungstabelle, umschaltbare Erklaerungs-Variante (Text/PDF).

## Detailabgleich

- **Reihenfolge Bestandteile**
  - FHDW: Titelblatt, optional Executive Summary, Verzeichnisse, Textteil, optional Anhang, Quellenverzeichnis, Ehrenwoertliche Erklaerung.
  - Template: entsprechend umgesetzt; Executive Summary per Schalter optional.

- **Raender**
  - FHDW: links ca. 4 cm, rechts ca. 2 cm, oben/unten ca. 2,5 cm.
  - Template: via `geometry` auf diese Werte gesetzt.

- **Schrift und Zeilenabstand**
  - FHDW: 12pt Times New Roman oder 11pt Arial, 1,5-zeilig.
  - Template: 12pt + Times-basierte Schrift (`newtxtext/newtxmath`) + `onehalfspacing`.

- **Seitennummerierung**
  - FHDW: vor Textteil roemisch (ohne Titelblatt), ab Textteil arabisch fortlaufend.
  - Template: bereits so umgesetzt.

- **Anhang und Anhangsverzeichnis**
  - FHDW: Anhaenge strukturiert, mit Nummerierung und Seitenangaben.
  - Template: separates `Anhangsverzeichnis` mit Pagerefs auf Anhangsteile.

- **KI-Nutzung**
  - FHDW/Fachbereichsvorgaben: Nutzung als Hilfsmittel offenlegen.
  - Template: eigene Datei `chapter/anhang/KI-Nutzungstabelle.tex` vorbereitet.

- **Ehrenwoertliche Erklaerung**
  - FHDW-Text inklusive KI-Hinweis: im Template enthalten.
  - Optional: offizielles PDF-Formular mit Feldern kann eingebunden werden.

## Offene Punkte fuer die individuelle Arbeit

- Dokumententyp, Titel, Namen, Pruefer, Studiengang, Matrikelnummer in `main.tex` pflegen.
- Umfangsvorgabe je Arbeitstyp (z. B. 12/25/40/60 Seiten) mit Betreuer abstimmen.
- Bei englischer Arbeit vorab Freigabe der Pruefer einholen.
- Bei vertraulichen Arbeiten Sperrvermerk in `main.tex` einkommentieren.
