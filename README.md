# LaTeX Basis-Template (FHDW, minimal)

**Aktueller Stand:** 20.04.2026

Dieses Repository ist als **gezielt minimalistisches Setup** fuer wissenschaftliche Arbeiten ausgelegt und laeuft ohne Sonderkonfiguration in **Overleaf**.

## Wichtiger Hinweis

Die enthaltenen Formalia wurden nach bestem Wissen an die FHDW-Vorgaben angepasst.  
Bitte pruefe vor der finalen Abgabe **eigenverantwortlich** alle aktuellen Richtlinien deiner Hochschule, deines Studiengangs und deiner Pruefer.

## Verwendung (kurz)

- Projekt in Overleaf importieren (ZIP-Upload oder Git).
- `main.tex` oeffnen und die Platzhalter (Titel, Name, Pruefer, Matrikelnummer etc.) anpassen.
- Inhalte in den Dateien unter `chapter/` schreiben.
- Literatur in `library/library.bib` pflegen.

## Schalter in `main.tex`

- `\mitexecutivesummarytrue` / `false`: Executive Summary ein- oder ausblenden.
- `\nutzepdferklaerungtrue` / `false`: offizielle PDF-Ehrenwoertliche Erklaerung statt Textvariante verwenden.

## Struktur (minimal)

- `main.tex`: Einstiegspunkt der Arbeit
- `config/config.tex`: Layout, Schrift, Pakete
- `chapter/`: Titelblatt, Kapitel, Anhang, Erklaerung
- `chapter/anhang/KI-Nutzungstabelle.tex`: Vorlage zur Dokumentation von KI-Nutzung
- `FORMALIEN_FHDW_2026.md`: kurzer Soll/Ist-Abgleich der Formalia

## Ziel des Templates

Ein schlankes Grundgeruest, das schnell startklar ist, gut in Overleaf funktioniert und nur die noetigen Pflichtbausteine mitbringt.
