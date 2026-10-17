# claude-vorlage

Vorlage für neue Projekte mit Claude Code: zwei Agenten (umsetzer auf Sonnet, pruefer auf Fable) und zwei Befehle.

## Neues Projekt starten

1. Oben auf **Use this template** → **Create a new repository** klicken.
2. In claude.ai/code eine Session mit dem neuen Repository starten und eintippen:
   `/projekt-start Was das Projekt werden soll`
3. Pull Request mergen. Danach pro Aufgabe: `/neue-funktion Beschreibung der Aufgabe`

## Inhalt

- `CLAUDE.md`: Projektsteckbrief, wird von /projekt-start ausgefüllt
- `.claude/settings.json`: Hauptsession auf Sonnet
- `.claude/agents/umsetzer.md`: baut und testet (Sonnet)
- `.claude/agents/pruefer.md`: prüft, ändert nichts (Fable)
- `.claude/skills/projekt-start/SKILL.md`: Befehl /projekt-start
- `.claude/skills/neue-funktion/SKILL.md`: Befehl /neue-funktion
