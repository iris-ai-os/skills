# IRIS Skills

Skills für IRIS als Plugin-Katalog für Claude (claude.ai, Desktop, iOS).

## Einrichten

1. In Claude unter Einstellungen, Funktionen die Codeausführung einschalten. Ohne sie lädt kein Skill.
2. Einstellungen, Plugins, Hinzufügen, Marketplace hinzufügen: `iris-ai-os/skills`.
3. Die gewünschten Plugins hinzufügen: `iris-core` für alle, weitere Pakete nach Bedarf.
4. Die IRIS-Verbindung (Konnektor) wird getrennt eingerichtet, die Plugins enthalten keine.
5. In den Einstellungen unter "Anweisungen für Claude" diese Zeile eintragen:
   `Ich nutze IRIS als mein persönliches Gedächtnis. Lade zu Beginn jedes Gesprächs den Skill iris-core und halte dich an seine Regeln. Frag mich nie nach Passwörtern.`
6. Prüfen: neues Gespräch, "IRIS-Check" schreiben.

## Aktualisieren

Einstellungen, Plugins, Hinzufügen, Marketplaces verwalten, beim Eintrag `iris-skills` auf "…" und "Nach Updates suchen".

## Pakete

- `iris-core`: Grundregeln (Skill `iris-core`), Morgen-Briefing, YouTube ins Brain
- `iris-netzwerk`: Netzwerk-Neuigkeiten

Die Skills verleihen keine Rechte. Was IRIS lesen oder schreiben darf, legen die Stufen der IRIS-Verbindung fest.
