---
titel: Annahmenprüfung
kurz: Findet tragende Annahmen und legt für jede einen Test fest
gruppe: Diagnose
---
# Annahmenprüfung

Macht sichtbar, auf welchen unbewiesenen Annahmen ein Plan oder eine Empfehlung ruht, ordnet sie nach Wirkung und Unsicherheit und legt für die kritischen einen schnellen Test fest.

## Wann einsetzen

- Ein Plan, Business Case oder eine Empfehlung liegt vor und soll belastbar werden: "Worauf verlassen wir uns hier eigentlich?"
- Vor einer großen Investition, um zuerst die billigsten Tests der gefährlichsten Annahmen zu machen.
- Nicht, um künftige Ereignisse mit Wahrscheinlichkeit zu bewerten. Das ist `references/risiken.md`.

## Schritte

1. **Aussage festlegen:** Welcher Plan oder welche Empfehlung wird geprüft? Ein Satz.
2. **Annahmen sammeln:** Frage für jeden Baustein: "Was muss wahr sein, damit das funktioniert?" Formuliere jede Annahme als prüfbaren Satz. Beispiel: "Fachhändler akzeptieren eine Marge, die zehn Prozentpunkte unter der heutigen liegt [Annahme, Zahl als Beispiel]." Denke an Kunden, Wettbewerb, eigene Fähigkeiten, Kosten, Zeit und Recht.
3. **Tragende Annahmen herausfiltern:** Streiche Annahmen, deren Wegfall am Ergebnis nichts ändert. Übrig bleiben die, ohne die der Plan kippt.
4. **Nach Wirkung und Unsicherheit ordnen:** je hoch, mittel oder gering, mit Halbsatz Begründung. Belegte Annahmen haben geringe Unsicherheit, Quelle angeben.
5. **Kritische Annahmen bestimmen:** hohe Wirkung und hohe Unsicherheit. Höchstens fünf, sonst ist der Plan noch zu unscharf.
6. **Test je kritischer Annahme:** Was wird geprüft, wie (Daten auswerten, Gespräche, Pilot, Vorbestellung), welches Ergebnis bestätigt, welches widerlegt, und wer bis wann. Wähle den billigsten Test, der eine klare Antwort liefert.
7. **Konsequenz festlegen:** Was ändert sich am Plan, wenn eine Annahme widerlegt wird?

## Output

- Die geprüfte Aussage als Satz.
- Eine Tabelle: Annahme, Wirkung, Unsicherheit, Beleg oder "[Annahme]".
- Eine Tabelle der kritischen Annahmen: Test, Bestätigungs- und Widerlegungskriterium, Rolle, Zeitpunkt, Konsequenz bei Widerlegung.

## Qualitätskriterium

Jede Annahme ist so formuliert, dass ein Test sie widerlegen kann, die Bewertung unterscheidet tatsächlich, und für jede kritische Annahme steht vorher fest, welches Ergebnis was bedeutet.

## Typischer Fehler

Annahmen als Wunsch statt als prüfbare Aussage ("Kunden mögen das Produkt") oder Tests ohne Kriterium, die jedes Ergebnis als Bestätigung lesen. Dann nachschärfen: Wer genau tut was, in welchem Umfang, und ab welchem Wert gilt die Annahme als widerlegt? Kritische Annahmen fließen in `references/business-case.md` als Sensitivitäten ein.
