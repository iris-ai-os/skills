# Ursachenanalyse (Ishikawa mit 5-Why)

Sammelt mögliche Ursachen einer unerwünschten Wirkung geordnet nach Ursachenfeldern (Fischgräte nach Ishikawa) und verfolgt die wichtigsten mit 5-Why bis zu einer Wurzel, die man beeinflussen kann.

## Wann einsetzen

- Ein Problem tritt auf oder droht: "Warum klappt X nicht?", "Was muss passieren, damit X nicht gelingt?"
- Nach einem KPI-Baum, um zu fragen, warum ein Treiber versagen könnte.
- Nicht für einzelne künftige Ereignisse mit Wahrscheinlichkeit. Das ist die Methode Risiken.

## Schritte

1. **Wirkung als einen Satz formulieren**, konkret und negativ. Beispiel: "Die Zahl der Kundentermine wächst über 12 Monate nicht." Sie steht am Kopf der Gräte.
2. **Äste wählen, vier bis acht.** Gibt es einen KPI-Baum, sind seine Hauptäste die ersten Äste. Sonst passend zum Thema, etwa Markt, Angebot, Zugang, Organisation, Kapazität, Nachweis, Partner, Messung. Die klassischen 6M (Mensch, Maschine, Methode, Material, Messung, Mitwelt) passen eher zu Produktion und Betrieb.
3. **Ursachen je Ast sammeln, zwei bis vier**, jede als Zustand formuliert: "X fehlt", "Y passiert zu spät". Keine Personen beschuldigen, sondern beschreiben, was im System fehlt.
4. **Belegen:** je Ursache die Quelle (IRIS-Seite, Aussage der Person) oder "[Annahme]".
5. **Gewichten:** Einfluss auf die Wirkung hoch, mittel oder gering. Wähle die drei Ursachen mit dem höchsten Einfluss, bei Gleichstand die belegten zuerst.
6. **5-Why für diese drei:** Frage "Warum?" so oft, bis eine Wurzel erreicht ist, die jemand beeinflussen kann, höchstens fünfmal. Endet die Kette außerhalb des eigenen Einflusses (Markt, Regulierung), halte dort an und schreibe das dazu.
7. **Maßnahme je Wurzel:** Verb, verantwortliche Rolle, Zeitpunkt oder "offen".

## Output

- Die Wirkung als Satz.
- Eine Tabelle: Ast, Ursache, Beleg, Einfluss.
- Für die drei stärksten Ursachen je eine 5-Why-Kette als nummerierte Liste, letzte Zeile die Wurzel.
- Eine Tabelle der Maßnahmen: Wurzel, Maßnahme, Rolle, Zeitpunkt.

## Qualitätskriterium

Jede Ursache erklärt die Wirkung und ist keine Umformulierung von ihr, die Äste überschneiden sich nicht, und jede Wurzel ist beeinflussbar oder ausdrücklich als nicht beeinflussbar markiert.

## Typischer Fehler

Symptome statt Ursachen ("zu wenige Termine" als Ursache für "Termine wachsen nicht") und 5-Why-Ketten, die bei einer Ausrede enden ("keine Zeit"). Dann weiterfragen: Warum fehlt die Zeit, und was davon lässt sich ändern?
