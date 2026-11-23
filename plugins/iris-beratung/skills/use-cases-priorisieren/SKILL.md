---
name: use-cases-priorisieren
description: >-
  Bewertet Prozessschritte auf Eignung für regelbasierte Automatisierung, wissensbasierte Agenten oder
  menschliches Urteil. Priorisiert Use Cases nach Wirkung, Aufwand, Datenlage und Folgen eines Fehlers
  und entwirft einen kontrollierten Pilot. Nutzen bei "Agenten-Use-Cases", "was automatisieren",
  "Impact-Effort", "KI im Prozess", "Agentic AI", "Pilot priorisieren".
---

# Use Cases priorisieren

Du suchst nicht den spektakulärsten, sondern den belegbar nützlichen und kontrollierbaren Einstieg. Lies `references/agenten-eignung.md`.

## Ablauf

1. Übernimm den Ist-Prozess aus `prozess-aufnehmen`. Fehlen Schritte, Volumen, Zeiten oder Fehlerfolgen, markiere die Bewertung als vorläufig.
2. Definiere je Kandidat Aufgabe, Eingang, gewünschtes Ergebnis, heutige Rolle und messbaren Engpass.
3. Ordne die Arbeitsart ein: regelbasiert, wissensbasiert oder Urteil nötig. Zerlege gemischte Schritte, statt den ganzen Schritt pauschal zu automatisieren.
4. Prüfe Daten: digital vorhanden, zugänglich, strukturiert, aktuell, vollständig und rechtmäßig nutzbar. Ein Dokument irgendwo im System bedeutet nicht automatisch nutzbare Daten.
5. Prüfe Fehlerfolgen: finanziell, rechtlich, sicherheitsrelevant, Kundenwirkung, Reversibilität und Erkennbarkeit. Leite daraus menschliche Freigabe, Stichprobe oder automatische Ausführung ab.
6. Bewerte Wirkung mit belegten Größen: eingesparte Bearbeitungszeit, kürzere Wartezeit, weniger Nacharbeit, bessere Qualität oder zusätzliche Kapazität.
7. Bewerte Aufwand: Integration, Datenaufbereitung, Ausnahmevielfalt, Tests, Betrieb, Überwachung und Veränderung der Arbeitsweise.
8. Trage Kandidaten in die Impact-Effort-Matrix ein. Ergänze Risiko als eigenes Tor: Ein Kandidat mit unbeherrschbarem Risiko ist kein Quick Win.
9. Empfiehl höchstens drei Kandidaten und einen Pilot. Der Pilot nennt Hypothese, Umfang, Vergleichsbasis, Erfolgskennzahl, Abbruchkriterium, Freigaben, Protokollierung und verantwortliche Rolle.
10. Übergib die Entscheidung an `storyline` und die Prüfung an `gegenpruefung`.

## Regeln

- Keine erfundenen Einsparungen. Rechne Bandbreiten und zeige den Rechenweg.
- Keine Bewertung einzelner Beschäftigter oder Empfehlung zum Stellenabbau.
- Menschliches Urteil bleibt verantwortlich, wenn Folgen schwer oder nicht reversibel sind.
- Ein Agent erhält nur die für die Aufgabe nötigen Daten und Rechte.
- IRIS schreibt nichts in das Wissen.
