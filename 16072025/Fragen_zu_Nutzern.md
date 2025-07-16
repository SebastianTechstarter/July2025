Was ist der Unterschied zwischen root, Standardbenutzer und Systemaccount?
- root ist DER Superuser mit allen Rechten.
- Standardbenutzer ist ein User mit eingeschränkten Rechten
- Systemaccounts sind spezielle Konten für Prozesse im Hintergrund

Was bedeutet es, wenn ein Befehl mit sudo ausgeführt wird?
- steht für "superuser do"
- führt Befehl mit root-Rechten aus

Wo stehen die Informationen zu einem Benutzer im System?
- /etc/passwd –-> Benutzername, UID, Home-Verzeichnis etc.
- /etc/shadow –-> zeigt verschlüsselte Passwörter und Passwort-Infos (nur für Root lesbar)
- /etc/group –-> zeigt Gruppenzugehörigkeiten an
- /etc/sudoers –-> regelt, wer sudo benutzen darf

Warum braucht ein neuer Benutzer erst zusätzliche Rechte, um sudo verwenden zu dürfen?
- Wenn jeder Nutzer root-Rechte hätte, dann wäre das ein erhebliches Sicherheitsrisiko
- Nur vertrauenswürdige Nutzer bekommen root-Rechte
- Jeder bekommt nur so viele Berechtigungen, wie notwendig sind, um Sicherheitslücken zu minimieren