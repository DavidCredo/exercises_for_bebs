# Navigation im Terminal
Im Terminal kannst du dich durch das komplette Dateisystem des Macs bewegen.
Ähnlich wie der Finder, bloß ohne GUI (Graphical User Interface).
Damit du nachher easy neue Dateien anlegen, kopieren und verschieben kannst,
schauen wir uns erstmal an, wie man sich effizient durch das System bewegt.
Dafür brauchen wir **Kommandos**.
Kommandos bestehen aus dem Kommando selbst, *flags*, wie zB. -a für das Kommando **ls** also => ls -a.
Manche Kommandos benötigen Argumente wie zB. cd. cd benötigt einen <Pfad> um zu funktionieren.
(Stimmt nicht 100%, aber das ist hier erstmal nicht so wichtig.)

## Wie sind Kommandos aufgebaut?
---
Hier sind ein paar sehr nützliche Kommandos
- **pwd** => *print working directory*
    - Gibt dir den Ordner aus in dem du dich gerade befindest. (nützlich, wenn du die Orientierung verlierst.)
- **cd `Pfad`** => *change directory*
    - hiermit bewegst du dich durch die Ordnerstruktur.
- **ls** => *list directory contents*
    - Gibt dir die Dateien und Ordner in dem aktuellen Ordner aus.
- **mkdir `Ordnername`** => *make directories*
    - Erzeugt die Verzeichnisse, die du als Argument angibst.
- **touch `Dateiname`** => Erzeugt Dateien, wenn sie noch nicht vorhanden sind. Wenn doch, kann man auch coole Sachen damit machen. Ist jetzt aber unnötig kompliziert.
---
Mehr Kommandos gibt's erstmal nicht. ;) 
Ein paar sehr nützliche habe ich dir vorenthalten, die sollst du selber finden.

Einen wichtigen Tipp noch bevor wir uns an die Aufgaben machen!
**Wenn du mehr über ein Kommando rausfinden willst, oder nicht mehr weißt, wie es funktioniert, gib in der Konsole einfach *man* + das Kommando ein.**
Also zB. `man cd`. Das bringt dich zur *manual* page des Kommandos.

## Aufgaben
Okay, genug davon. 
Lass uns das ganze mal anwenden!

### Urlaubs-Ordner
1. Öffne das Terminal und gib dir das working directory aus.
2. Erstelle einen Ordner mit dem Name **Urlaub_Herbst22**
3. Wechsel in den neuen Ordner.
4. Erstelle hier zwei Unterordner 
    - Der erste Ordner soll **Planung** heißen
    - Der zweite Ordner soll **Fotos** heißen
5. Wechsel nun in den **Planung** Ordner
    - Erzeuge eine Datei mit dem Namen **Packliste.txt** (Dateiendung beachten!)
6. Gib dir die Dateien im aktuellen Ordner in der Konsole aus.
7. Gehe einen Ordner zurück, also in den Parent Ordner. (Wie kann man das machen? :) )
8. Lass dir auch hier wieder die Dateien und Ordner in der Konsole ausgeben.
9. **Fertig!**

