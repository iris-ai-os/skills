---
titel: Business Case
kurz: Rechnet den Mehrwert einer Investition gegen den Basisfall
gruppe: Entscheidung
---
# Business Case

Rechnet aus, was eine Investition gegenüber dem Basisfall ohne Investition zusätzlich einbringt und kostet, über die Zeit verteilt, und zeigt mit Kapitalwert, Amortisation und Sensitivität, wie belastbar das Ergebnis ist.

## Wann einsetzen

- Eine Investition, ein Projekt oder eine Option soll wirtschaftlich beurteilt werden: "Rechnet sich das?"
- Als Bewertung des Wertbeitrags in `references/optionen.md`.
- Nicht, wenn der Nutzen überwiegend nicht in Geld fassbar ist (etwa Pflicht durch Regulierung). Dann nur die Kosten der günstigsten zulässigen Lösung vergleichen.

## Schritte

1. **Basisfall festlegen:** Was passiert ohne Investition? Der Basisfall ist selten "alles bleibt gleich", oft verschlechtert er sich. Beispiel: Ein Hersteller von Fahrradteilen verliert ohne Direktvertrieb jedes Jahr Absatz im Fachhandel [Annahme].
2. **Investitionsfall beschreiben:** was genau getan wird, ab wann, mit welchem Umfang.
3. **Treiber bestimmen:** Größen, die den zusätzlichen Nutzen ergeben, als Rechnung, etwa Menge × Preis × Deckungsbeitragsquote. Für die Struktur `references/kpi-baum.md`. Je Treiber Wert und Quelle oder "[Annahme]".
4. **Kosten erfassen:** einmalige Investitionen, laufende Kosten, Anlaufverluste, Kosten für Personal und Umstellung. Nichts vergessen, was nur im Investitionsfall anfällt.
5. **Zeitprofil aufstellen:** je Jahr Differenz zwischen Investitionsfall und Basisfall, über drei bis fünf Jahre. Anlaufkurven realistisch ansetzen, volle Wirkung selten im ersten Jahr.
6. **Kennzahlen berechnen:** Kapitalwert mit einem begründeten Zinssatz [Annahme, falls nicht vorgegeben], Amortisationszeit, kumulierter Mittelabfluss im schlechtesten Jahr.
7. **Sensitivität prüfen:** Variiere die zwei bis drei stärksten Treiber in einer plausiblen Spanne und zeige, wie sich der Kapitalwert ändert. Nenne den Schwellenwert, ab dem sich die Investition nicht mehr lohnt.

## Output

- Basisfall und Investitionsfall je in zwei bis drei Sätzen.
- Eine Tabelle der Annahmen: Treiber, Wert, Quelle oder "[Annahme]".
- Eine Tabelle des Zeitprofils je Jahr: zusätzlicher Nutzen, Kosten, Differenz, kumuliert.
- Kapitalwert, Amortisation, größter Mittelabfluss.
- Eine Sensitivitätstabelle mit Schwellenwerten und ein Satz, wie belastbar das Ergebnis ist.

## Qualitätskriterium

Gerechnet wird nur die Differenz zum Basisfall, jede Zahl ist belegt oder markiert, und die Sensitivität zeigt, bei welchem Wert eines Treibers das Ergebnis kippt.

## Typischer Fehler

Den Investitionsfall gegen "heute" statt gegen den Basisfall rechnen oder Nutzen bereits im ersten Monat voll ansetzen. Ebenso häufig: Ein Punktwert ohne Sensitivität, der Sicherheit vortäuscht. Dann die schwächsten Annahmen über `references/annahmenpruefung.md` prüfen.
