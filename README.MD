# teska-mblock5
Wie man die install files bekommt:
1. installiert mblock erstmal auf einem Rechner
2. wechselt dann ins Install Verzeichnis und kopiert den Inhalt nach mblock in CLIENT_DATA
3. damit auch der Serielle Driver mit kommt, müsst Ihr die Install files für die Treiber nach driver in CLIENT_DATA legen
4. danach noch ein opsi-set-rights
5. Paket mit opsimakepackage generieren
6. Paket mit opsi-package-manger -i teska-mblock* installieren
7. Refresh vom opsi config editor

