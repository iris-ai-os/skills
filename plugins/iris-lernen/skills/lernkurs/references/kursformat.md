# Format der Kursseiten

Die Seite Lernen im Portal liest die Seiten alle fünf Minuten aus dem Wissen. Sie versteht nur dieses Format; was nicht passt, bleibt im Wissen, fehlt aber im Portal.

## Kursseite `lernen/<kurs>`

`<kurs>` nur Kleinbuchstaben, Ziffern und Bindestriche, zum Beispiel `lernen/versicherungen`.

```
---
type: concept
art: lernkurs
beschreibung: Ein Satz, worum es geht und wofür.
---
# Versicherungen

Ziel, Vorwissen und Quellen in wenigen Sätzen. Verweise auf alte Notizen per Wikilink.
```

## Kapitelseite `lernen/<kurs>/<kapitel>`

`<kapitel>` wie oben, zum Beispiel `lernen/versicherungen/grundbegriffe`. `reihenfolge` legt die Folge im Kurs fest (1, 2, 3 ...).

```
---
type: concept
art: lernkapitel
reihenfolge: 1
---
# Grundbegriffe

## Lesen

### Wie Versicherung funktioniert
Kurze Absätze. Listen mit "- " sind erlaubt.

### Wer was zahlt
Weiterer Abschnitt.

## Begriffe

- **Prämie**: Preis, den man für den Versicherungsschutz zahlt.
- **Selbstbeteiligung**: Teil des Schadens, den man selbst trägt.

## Fragen

### Wer versichert die Versicherer?
- [ ] Die Bundesbank
- [x] Rückversicherer
- [ ] Niemand
> Erklärung: Rückversicherer übernehmen einen Teil der Risiken von Erstversicherern.

### Welche Versicherungen sind in Deutschland für alle Pflicht? Wählen Sie zwei.
- [x] Krankenversicherung
- [ ] Hausratversicherung
- [x] Pflegeversicherung
- [ ] Reisegepäckversicherung
> Erklärung: Kranken- und Pflegeversicherung sind Pflicht, Hausrat und Reisegepäck freiwillig.
```

## Regeln

- Die drei Abschnitte heißen genau `## Lesen`, `## Begriffe` und `## Fragen`. Andere Abschnitte (etwa `## Notizen`) sind erlaubt, das Portal zeigt sie nicht.
- **Lesen:** Abschnitte mit `###` und Titel. Text vor dem ersten `###` ist ein Abschnitt ohne Titel.
- **Begriffe:** eine Zeile je Karte, genau `- **Begriff**: Erklärung`. Begriff höchstens ein paar Wörter, Erklärung ein Satz. Jeder Begriff nur einmal im Kapitel.
- **Fragen:** je Frage eine Zeile `### Frage?`, darunter zwei bis acht Antworten mit `- [ ]`, mindestens eine mit `- [x]`, optional eine Zeile `> Erklärung: ...`. Fragen ohne richtige Antwort zeigt das Portal nicht.
- **Mehrfachauswahl:** Hat eine Frage zwei oder mehr `- [x]`, zeigt das Portal Kontrollkästchen mit dem Hinweis „Mehrere Antworten richtig“. Richtig ist sie nur, wenn genau die richtigen Antworten gewählt sind, wie in Zertifizierungsprüfungen. Wie viele richtig sind, darf in der Frage stehen („Wählen Sie zwei.“); mindestens eine Antwort sollte falsch sein.
- Ein Kapitel ohne Kursseite zeigt das Portal nicht.
- Begriff und Frage sind der Schlüssel des Lernstands: Wer sie umformuliert, beginnt die Karte neu. Erklärungen und Antworten dürfen sich ändern.
- Kein Kursinhalt in den Kopf schreiben, nur `type`, `art`, `beschreibung` und `reihenfolge`.
