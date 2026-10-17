---
name: neue-funktion
description: Baut eine Funktion oder Fehlerbehebung mit dem umsetzer und lässt sie vom pruefer prüfen.
argument-hint: [Beschreibung der Aufgabe]
disable-model-invocation: true
---

Aufgabe: $ARGUMENTS

Arbeite so:
1. Lass den Subagent "umsetzer" die Aufgabe umsetzen und testen.
2. Lass danach den Subagent "pruefer" die Änderungen prüfen.
3. Meldet der pruefer "ÄNDERUNGEN NÖTIG", gib seine Befunde an den umsetzer
   zurück und lass danach erneut prüfen. Höchstens 3 Runden.
4. Bei "FREIGEGEBEN": Erstelle einen Pull Request und fasse für mich in
   einfachen Worten zusammen, was gebaut wurde und was der pruefer
   angemerkt hat.
5. Nach 3 Runden ohne Freigabe: Erkläre mir, woran es hängt, und frag mich,
   wie es weitergehen soll.

Ändere selbst keinen Code. Das macht nur der umsetzer.
