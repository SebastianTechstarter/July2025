## Was ist der Vorteil von useradd im Vergleich zu adduser?
- useradd fragt nicht nach Details --> Ideal für automatisierte Benutzererstellung
- ganz präzise, da alle erforderlichen Informationen direkt mitgegeben werden.

## Was macht die Option -G bei useradd?
- Damit kann man den neuen Nutzer direkt zu mehreren Gruppen hinzufügen

## Was bewirkt chmod 777 datei.txt?
- vergibt Lese-/Schreib-/Ausführrechte an:
    - User (Eigentümer) --> erste 7
    - Gruppe            --> zweite 7
    - Others (alle weiteren Nutzer) --> dritte 7

## Wozu dient der Befehl chown benutzer:gruppe datei.txt?
- Ändert den Eigentümer (User) und die Gruppe der Datei "datei.txt"

## Was ist der Zweck des Sticky Bits in /tmp?
- Das Sticky Bit sorgt dafür, dass nur der Eigentümer und der Root Dateien löschen können, unabhängig davon, ob die anderen User Schreibrechte haben.
- Schützt vor Missbrauch in gemeinsam genutzten Verzeichnissen und Dateien.