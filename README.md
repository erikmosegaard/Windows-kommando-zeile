# Windows-kommando-zeile
Gruppe: Halid, Michel, Erik, Yannis, Supatra
---
## comp oder fc

Vergleicht den Inhalt zweier Dateien und stellt die Unterschiede dar
#### (comp: compare / fc: file compare)

---
## (x)copy/robocopy

**copy** -> eine oder mehrere Dateien kopieren

**xcopy** -> erweiterte version von **copy**

**robocopy** -> Kopieren und Synchronisieren von Verzeichnissen, Bricht bei Fehler nicht ab
---
Erik
####del / erase
del und erase ist das selbe.
Löscht eine Datei, die sich im aktuellen Verzeichnis befindet. Als Parameter muss mindestens der Dateiname angegeben werden. Weitere Parameter sind optional:
/p - jede datei muss einzelne Löschung bestätigt werden.
/f - schreibgeschützte Dateien löschen.
/s - löscht Dateien, in Unterverzeichnissen.
/q - Unterbindet Bestätigung.
Beim beispiel wird zulöschendedatei ohne bestätigung gelöscht mit den dateien in den unterverzeichnisse.
```del C:\zulöschendedatei.bat /q /s```


#### deltree

Um ganze Verzeichnisse zulöschen sollte man
```DELTREE c:\Modul302```
Löscht Verzeichnis(se) inkl. untergeordnete Dateien.
XP rmdir/rd. Deltree kennt xp nicht mehr. Anmerkung: rmdir/rd keine Wildcards ('*' '?') im Verzeichnisnamen.
```rmdir c:\Modul302```
Unter Windows XP rmdir für Deltree
rmdir/rd versteht keine Wildcards ('*' oder '?') im Verzeichnisnamen.
