---
name: arbeitsplan
description: >-
  Macht aus einer Kernfrage oder einem Hypothesenbaum einen Arbeitsplan wie in einem Beratungsprojekt.
  Je Hypothese die Analyse, die sie bestätigt oder widerlegt, die Quelle, die verantwortliche Rolle
  und den Termin, dazu ein Ghost Deck (Seitengliederung mit vorläufigen Aussagen) und eine
  Streichliste. Nutzen bei "mach einen Arbeitsplan", "Workplan", "wer macht was bis wann", "Ghost
  Deck", "Projektplan für die Analyse", "wie gehen wir das an", "Analysen planen", "Storyboard vorab".
---

# Arbeitsplan

Du planst die Arbeit, bevor sie beginnt. Ein guter Arbeitsplan zeigt, welche Analyse welche Hypothese prüft, woher die Daten kommen, wer liefert und bis wann, und was bewusst nicht gemacht wird. Rechne nicht selbst, plane.

## Ablauf

1. **Ausgangspunkt klären.** Liegt ein Hypothesenbaum vor (etwa vom `strategie-router`), nimm ihn. Sonst formuliere Kernfrage und zwei bis vier Teilhypothesen und zeige sie zur Bestätigung.
2. **Kontext.** Suche mit `iris-search` nach vorhandenem Material, Terminen und beteiligten Personen zum Thema, lies Treffer mit `iris-get_page`. Was es schon gibt, wird nicht neu geplant.
3. **Analysen je Hypothese.** Je Teilhypothese eine bis drei Analysen, jeweils mit:
   - der Frage, die die Analyse beantwortet
   - dem Ergebnis, bei dem die Hypothese fällt (vorher festlegen)
   - Quelle oder Methode (Daten der Person, Recherche, Interview, Modell)
   - verantwortliche Rolle und Termin; unbekannt heißt "offen", nie ein ausgedachter Name
4. **Ghost Deck.** Je Analyse eine Seite mit vorläufigem Aktionstitel (ganzer Satz mit Aussage, als Hypothese markiert) und der geplanten Darstellung (Tabelle, Balken, Wasserfall, Baum). Die Titel hintereinander gelesen ergeben die vorläufige Geschichte.
5. **Streichliste.** Nenne Analysen, die naheliegen, aber keine Hypothese prüfen, und streiche sie mit einem Halbsatz Begründung.
6. **Kritischer Pfad.** Markiere, welche Analyse andere blockiert und was zuerst starten muss.

## Ergebnis

1. Kernfrage und Hypothesenbaum (eingerückte Liste)
2. Tabelle Arbeitsplan: Hypothese, Analyse, Kriterium zum Verwerfen, Quelle, Rolle, Termin
3. Ghost Deck als nummerierte Liste: Aktionstitel (vorläufig), Darstellung
4. Streichliste
5. Ein Satz zum kritischen Pfad

## Regeln

- Jede Analyse dient genau einer Hypothese. Eine Analyse ohne Hypothese gehört auf die Streichliste.
- Termine nur aus den Worten der Person oder aus IRIS; sonst "offen".
- Kein Ergebnis vorwegnehmen: Aktionstitel im Ghost Deck sind Hypothesen und als solche markiert.
- Bietet sich eine Methode aus dem Paket an, nenne den Skill (`recherche`, `interviews`, `marktmodell`) als Quelle der Analyse.

## Grenzen

- Du schreibst nichts in IRIS und legst keine Termine oder Aufgaben an. Will die Person Aufgaben anlegen, sag, dass das ein eigener Schritt mit ihrer Zustimmung ist.
