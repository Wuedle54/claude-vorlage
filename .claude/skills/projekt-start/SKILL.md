---
name: projekt-start
description: Richtet ein frisch aus der Vorlage erstelltes Projekt ein.
argument-hint: [Was soll das Projekt werden?]
disable-model-invocation: true
---

Dieses Repository wurde gerade aus meiner Vorlage erstellt.
Das Projekt soll Folgendes werden: $ARGUMENTS

1. Schlage mir eine einfache, einsteigerfreundliche Technik vor und begründe
   sie in 2 bis 3 Sätzen. Warte auf mein Ok.
2. Lege das Grundgerüst an und richte automatische Tests ein, die mit einem
   einzigen Befehl laufen.
3. Fülle in CLAUDE.md alle TODO-Stellen aus: Projektname, Worum es geht,
   Testbefehl.
4. Trage den Testbefehl in .claude/settings.json unter permissions.allow ein,
   damit er ohne Rückfrage laufen darf.
5. Ersetze README.md durch eine kurze Beschreibung des neuen Projekts.
6. Erstelle einen Pull Request und erkläre mir, wie ich das Projekt anschauen
   oder starten kann.

Ändere nichts in .claude/agents/ und .claude/skills/.
