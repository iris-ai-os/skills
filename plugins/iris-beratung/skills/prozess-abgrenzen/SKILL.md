---
name: prozess-abgrenzen
description: >-
  Grenzt einen Prozess mit SIPOC ab und übersetzt Kundenstimmen mit einem CTQ-Baum in messbare
  Anforderungen. Nutzen bei "SIPOC", "Prozessgrenze", "Lieferanten und Eingaben", "wer ist der
  Kunde", "Voice of Customer", "CTQ", "Kundenanforderung messbar machen".
---

# Prozess abgrenzen

Du klärst, welcher Prozess untersucht wird und woran gute Qualität erkennbar ist. Lies `references/sipoc-ctq.md`.

## Ablauf

1. Übernimm Auftrag und Ziel aus `prozess-router` oder kläre sie kurz.
2. Suche mit `iris-search` nach Prozessbeschreibungen, Kundenstimmen und Kennzahlen; lies passende Seiten mit `iris-get_page`. Kennzeichne Aussagen als `angegeben`, `gefunden` oder `angenommen`.
3. Baue SIPOC in der Reihenfolge Prozess, Ergebnis, Kundin, Eingaben, Lieferanten. Beschreibe den Prozess zunächst in fünf bis sieben groben Schritten.
4. Prüfe Startsignal und Endereignis. Nenne ausdrücklich, was außerhalb liegt.
5. Sammle Kundenstimmen wortgetreu, ohne sie sofort in Lösungen umzudeuten.
6. Baue je Stimme einen CTQ-Baum: Bedürfnis, Qualitätstreiber, messbares Merkmal, Definition, Einheit, Datenquelle und Zielwert. Fehlende Zielwerte bleiben offen.
7. Prüfe Konflikte zwischen CTQs, etwa Schnelligkeit gegen Sorgfalt, und schlage eine Entscheidung vor.
8. Gib SIPOC, CTQ-Baum, Annahmen und Fragen für die Prozessaufnahme aus.

## Qualitätsprüfung

- Hat der Prozess genau ein Startsignal und ein Endereignis?
- Ist jede Eingabe einem Lieferanten und jedes Ergebnis einer Kundin zugeordnet?
- Ist jedes CTQ beobachtbar oder messbar, ohne eine Lösung vorzugeben?
- Sind Nenner, Einheit, Zeitraum und Datenquelle jeder Kennzahl definiert?

## Regeln

- Keine erfundenen Zielwerte oder Kundenstimmen.
- Personenbezogene Einzelfälle nur aggregiert beschreiben.
- IRIS schreibt nichts in das Wissen.
- Übergib für den detaillierten Ist-Ablauf an `prozess-aufnehmen`.
