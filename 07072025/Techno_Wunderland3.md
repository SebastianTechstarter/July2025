## Die Geschichte von Alex, dem neuen Linux-Administrator

Alex hat gerade seinen ersten Job als Junior-Systemadministrator bei der Firma "TechnoWunderland GmbH" bekommen. Das Unternehmen entwickelt innovative Apps für Smartphones und benötigt einen gut organisierten Linux-Server. Alex muss verschiedene Aufgaben bewältigen, um das System zu verwalten und dabei die Grundlagen der Befehlszeile meistern.

---

## **Teil 3: Dateien suchen und finden**

### Aufgabe 9: Die verlorenen Projektdateien 📁
Alex hat erfahren, dass sein Vorgänger wichtige Projektdateien irgendwo im System versteckt hat.

**Ihre Aufgaben:**
1. Erstellen Sie zunächst ein Testszenario:
   - Erstellen Sie Verzeichnisse: `~/projekte/app1`, `~/projekte/app2`, `~/backup`
   - Erstellen Sie Dateien: `projekt_alpha.txt`, `projekt_beta.doc`, `backup_projekt.txt`
2. Nutzen Sie `locate` um alle Dateien zu finden, die "projekt" enthalten
3. Nutzen Sie `find` um alle `.txt` Dateien in Ihrem Home-Verzeichnis zu finden
4. Nutzen Sie `find` um alle Dateien zu finden, die in den letzten 10 Minuten geändert wurden

**Befehle zu verwenden:** `mkdir`, `touch`, `locate`, `find`

---

### Aufgabe 10: Das Backup-Dilemma 💾
Alex muss herausfinden, welche Backup-Dateien älter als eine Woche sind und gelöscht werden können.

**Ihre Aufgaben:**
1. Erstellen Sie mehrere Testdateien mit verschiedenen Datums-Stempeln:
   - `backup_alt.tar` (versuchen Sie, das Datum zu ändern)
   - `backup_neu.tar`
   - `backup_config.conf`
2. Nutzen Sie `find` um:
   - Alle `.tar` Dateien zu finden
   - Alle Dateien zu finden, die größer als 0 Bytes sind
   - Alle Dateien zu finden, die das Wort "backup" im Namen haben
3. Kombinieren Sie `find` mit `ls -l` um Details der gefundenen Dateien anzuzeigen

**Befehle zu verwenden:** `touch`, `find`, `ls`