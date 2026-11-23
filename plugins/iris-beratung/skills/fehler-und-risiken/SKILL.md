---
name: fehler-und-risiken
description: >-
  Analysiert Prozessfehler und Risiken mit Pareto und Prozess-FMEA, übergibt Ursachenfragen an die
  vorhandene Ursachenanalyse und erstellt Maßnahmen plus Kontrollplan. Nutzen bei "Pareto",
  "häufigste Fehler", "FMEA", "Prozessrisiko", "5-Why", "Ishikawa", "Fehler vermeiden",
  "Verbesserung absichern", "Kontrollplan".
---

# Fehler und Risiken

Du priorisierst auf Basis von Daten, nicht nach Lautstärke. Lies `references/pareto-fmea.md`.

## Modus wählen

- **Pareto:** Fehlerdaten liegen vor und sollen priorisiert werden.
- **Ursachen:** Ein priorisierter Fehler soll erklärt werden.
- **FMEA:** Prozessschritte sollen vorbeugend auf Risiken geprüft werden.
- **Control:** Eine Verbesserung soll mit Kennzahl und Reaktionsplan stabil bleiben.

## Ablauf

1. Kläre Fehlerdefinition, Einheit, Zeitraum, Grundgesamtheit und Quelle. Trenne Anzahl betroffener Fälle von Anzahl Fehlerereignisse.
2. Bereinige Kategorien nur nachvollziehbar. Behalte Rohbezeichnung und Zuordnung.
3. Erstelle für Pareto eine absteigend sortierte Tabelle mit Anzahl, Anteil und kumuliertem Anteil. Nenne Gesamtzahl und fehlende Werte. Die 80-Prozent-Grenze ist Orientierung, kein Naturgesetz.
4. Übergib für Ishikawa und 5-Why an die Ursachenanalyse des `strategie-router`; kopiere sie nicht. Fordere für jede Ursache einen möglichen Gegenbeleg und eine Prüfung.
5. Baue für FMEA je Prozessschritt Funktion, Fehlermodus, Folge, Ursache, bestehende Vorbeugungs- und Entdeckungskontrolle auf.
6. Lass Schwere, Auftreten und Entdeckung von den verantwortlichen Fachrollen begründen. Dokumentiere Skala, Beleg und Unsicherheit.
7. Priorisiere hohe Schwere zuerst, dann schwache Vorbeugung und Entdeckung. Eine offizielle Action Priority nach AIAG und VDA 2019 darf nur mit einer bereitgestellten, berechtigt genutzten AP-Tabelle vergeben werden. Sonst heißt das Feld `vorläufige Priorität`, nicht Action Priority.
8. Formuliere Maßnahmen mit verantwortlicher Rolle, Termin, erwarteter Wirkung und neuer Bewertung nach Umsetzung.
9. Erstelle für Control Kennzahl, Erhebungsrhythmus, Grenze, verantwortliche Rolle und Reaktion bei Abweichung.

## Regeln

- Multipliziere Bewertungen nicht zu einer scheinpräzisen Risikoprioritätszahl, wenn die verwendete Methode Action Priority verlangt.
- Hohe Schwere darf nicht durch seltenes Auftreten kleingerechnet werden.
- Korrelation oder zeitliches Zusammentreffen ist kein Ursachenbeleg.
- IRIS schreibt nichts in das Wissen.
- Übergib entscheidungsreife Ergebnisse an `storyline` und lasse sie mit `gegenpruefung` prüfen.
