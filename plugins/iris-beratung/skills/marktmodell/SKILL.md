---
name: marktmodell
description: >-
  Rechnet Marktgröße und Business Case als nachvollziehbares Modell, wie ein Analyst es in Excel baut.
  Marktgröße von oben und von unten mit Abgleich, Business Case mit Basisfall, Investition,
  Kapitalwert und Amortisation, Sensitivität und Szenarien. Trennt Annahmen, Rechnung und Ergebnis,
  nennt je Annahme die Quelle und liefert auf Wunsch eine Excel-Datei. Nutzen bei "rechne den Markt",
  "Marktgröße", "Marktpotenzial", "TAM SAM SOM", "Business Case rechnen", "lohnt sich das",
  "Kapitalwert", "Amortisation", "Sensitivität", "Szenarien", "Excel-Modell", "Abschätzung".
---

# Marktmodell

Du baust ein Rechenmodell, das eine andere Person nachrechnen und ändern kann. Die Zahl am Ende ist weniger wichtig als die Annahmen dahinter: Sie müssen sichtbar, belegt und einzeln änderbar sein.

## Ablauf

1. **Frage und Ergebnisgröße.** Was soll das Modell beantworten (Marktgröße in Euro pro Jahr, Kapitalwert einer Investition), für welche Region und welchen Zeitraum? Methoden im Detail: `references/marktgroesse.md` und `references/business-case.md` im Skill `strategie-router`, falls dieser installiert ist; sonst die Schritte hier.
2. **Annahmen sammeln.** Suche zuerst in IRIS (`iris-search`, `iris-get_page`) nach eigenen Zahlen, dann nutze vorhandene Recherchen (Skill `recherche`). Je Annahme: Wert, Einheit, Quelle, Vertrauensstufe. Ohne Quelle heißt sie "[Annahme]" und bekommt eine Bandbreite.
3. **Marktgröße (falls gefragt).**
   - Von oben: Gesamtmarkt aus einer Quelle, dann schrittweise auf das relevante Segment eingrenzen.
   - Von unten: Zahl der Kunden mal Bedarf je Kunde mal Preis.
   - Abgleich: Liegen beide Wege mehr als ein Drittel auseinander, suche den Grund, bevor du weiterrechnest.
4. **Business Case (falls gefragt).** Basisfall ohne Maßnahme gegen Fall mit Maßnahme, Unterschied je Jahr: Umsatz, Kosten, Investition, laufende Kosten. Daraus Kapitalwert mit genanntem Zinssatz, Amortisationsjahr, Spitzenbedarf an Geld.
5. **Sensitivität.** Verändere die drei stärksten Treiber einzeln (etwa plus und minus 20 Prozent) und zeige die Wirkung auf das Ergebnis. Nenne den Schwellenwert, ab dem die Empfehlung kippt.
6. **Szenarien.** Vorsichtig, Basis, ambitioniert, jeweils mit benannten Annahmen, nicht nur mit Aufschlägen.
7. **Plausibilität.** Passt das Ergebnis zur Welt (Anteil am Gesamtmarkt, Umsatz je Mitarbeiter, Vergleich mit bekannten Anbietern)? Auffälligkeiten nennen.

## Excel-Datei (auf Wunsch)

Kann die Unterhaltung Dateien erzeugen, baue eine Excel-Datei mit drei Blättern: **Annahmen** (eingefärbte Eingabezellen mit Quelle je Zeile), **Rechnung** (nur Formeln, keine fest eingetippten Zahlen), **Ergebnis** (Kennzahlen, Sensitivität, Szenarien). Kann sie das nicht, liefere die Tabellen im Text so, dass sie sich übertragen lassen.

## Ergebnis

1. Antwort zuerst: Ergebnis als Bandbreite mit dem wahrscheinlichsten Wert und einem Satz zur Einordnung.
2. Tabelle der Annahmen mit Quelle und Vertrauensstufe.
3. Rechenweg in nachvollziehbaren Schritten.
4. Sensitivität und Szenarien, Schwellenwert der Entscheidung.
5. Grenzen des Modells.

## Regeln

- Keine Zahl ohne Quelle oder Markierung als Annahme. Keine Scheingenauigkeit: runde passend zur Unsicherheit.
- Einheiten und Zeiträume bei jeder Zahl. Nominal oder real, netto oder brutto ausdrücklich nennen.
- Steuer-, Bilanz- und Finanzierungsfragen nur als Hinweis; das Modell ersetzt keine Beratung dazu.
- Du schreibst nichts in IRIS.
