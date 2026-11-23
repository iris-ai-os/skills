---
name: prozess-aufnehmen
description: >-
  Nimmt den Ist-Prozess als Swimlane und Wertstrom auf: Rollen, Aktivitäten, Entscheidungen,
  Übergaben, Wartezeit, Bearbeitungszeit, Mengen, Nacharbeit und Daten. Bewertet je Schritt die
  Eignung für Agenten. Nutzen bei "Prozess aufnehmen", "Swimlane", "BPMN", "Value Stream Map",
  "Wertstrom", "Durchlaufzeit", "Wartezeit", "Nacharbeit", "Medienbruch".
---

# Prozess aufnehmen

Du dokumentierst den beobachteten Ist-Zustand. Lies `references/swimlane-wertstrom.md`. Eine gewünschte Zukunftslösung gehört erst nach der Ist-Aufnahme in ein Soll-Bild.

## Ablauf

1. Übernimm Grenze, Kundin und CTQs aus `prozess-abgrenzen`. Fehlen sie, markiere die Lücke.
2. Lies vorhandenes Material mit `iris-search` und `iris-get_page`. Trenne beobachtete, angegebene und angenommene Schritte.
3. Liste Ereignisse, Rollen, Aktivitäten, Entscheidungen, Systeme, Ein- und Ausgaben in zeitlicher Reihenfolge.
4. Baue eine Swimlane-Tabelle. Jede Zeile enthält laufende Nummer, Rolle, Aktivität, Eingang, Ausgang, System, Entscheidung, Übergabe und Belegstatus.
5. Ergänze Wertstromdaten: Fallmenge, Bearbeitungszeit, Wartezeit, Bestände, First-pass yield und Nacharbeit. Nutze Bandbreiten, wenn die Daten streuen.
6. Markiere Verschwendung nur mit beobachtbarem Hinweis: Warten, Übergabe, Rückfrage, Suche, Doppelarbeit, Nacharbeit, Bestand oder unnötige Freigabe.
7. Bewerte jeden Schritt im Raster `references/swimlane-wertstrom.md`: regelbasiert, wissensbasiert oder Urteil nötig; Daten digital; Folgen eines Fehlers; menschliche Freigabe.
8. Prüfe Summen. Durchlaufzeit ist nicht die Summe geschätzter Mittelwerte, wenn Fälle unterschiedliche Pfade nehmen.
9. Gib Ist-Bild, Datenlücken, Engpässe und Übergabe an `fehler-und-risiken` aus.

## BPMN-Ausgabe

Wenn Dateien erzeugt werden können und die Person BPMN verlangt, erstelle zusätzlich eine BPMN-2.0-Datei. Nutze genau ein Start- und mindestens ein Endereignis, Aufgaben für Aktivitäten, Gateways nur für echte Entscheidungen und Nachrichtenflüsse nur zwischen getrennten Beteiligten. Validiere XML und Kontrollfluss. Andernfalls liefere ein eindeutiges BPMN-Briefing als Tabelle, nicht scheinbar gültiges XML.

## Regeln

- Keine Zeit, Menge oder Quote ohne Quelle oder Kennzeichnung `[Annahme]`.
- Keine Bewertung der Leistung einzelner Personen.
- Varianten und Ausnahmen nicht in einen vermeintlichen Standardpfad zwingen.
- IRIS schreibt nichts in das Wissen.
