# Tool-Supported-Data-Cleaning

## Aufgabe 1
<br><br>

### Daten Hochladen
<br>
Ich habe die Daten als CSV-Datei gespeichert und auf trifacta hochgeladen (siehe Screenshot)
<br><br>

![Initial Data](trifacta_upload.png)


1- Zuerst werden alle Zeilen gelöscht, die kein gültes Alter haben. <br>
2- Alle Zeilen ohne ID werden gelöscht. Sie könnten später manuell hinzugefügt worden sein. <br>
3- Alle Zeilen werden gelöscht, die keinen "full_name" haben. <br>
4- Alle Zeilen werden gelöscht, die keine E-Mail Adresse haben. <br>
5- Alle Zeilen werden gelöscht, die kein Gender haben. <br>
6- Um später Duplikate zu identifizieren, werden die "id" gelöscht. <br>
7- Duplikate werden gelöscht.<br> <br>

![Recipe](Recipe.png)


### Ergebnis
<br>
Am Ende wurde das Ergebnis in der Datei "dsm-beuth-edl-demodata-clean.csv" gespeichert.
<br><br>

![Clean Data](Clean.png)

<br><br>
## Aufgabe 2

<br>
Wenn man die Daten hochgeladen hat, ist es möglich zu sehen, wo trifacta mögliche Fehler gefunden hat. Hier gibt es 3 Zeilen mit Missmatch und 2 Zeilen, mit fehleden Daten (siehe Screenshot).
<br><br>

![Grid Disruption: mögliche Fehler](Grid_Dis_Initial_Prob.png)

<br><br>

Auf dem folgenden Screenshot kann man sehen, dass es Zellen gibt, die kein Datum haben.

<br><br>

![Grid Disruption: Fehler bei dem Datum](Display_Errors.png)

<br><br>

Auf dem folgenden Screenshot sind weitere Beispiele von Fehlern zu sehen
<br><br>
![Grid Disruption: Fehler bei dem Datum](Display_Errors2.png)

<br><br>

Die Anzahl der Zeilen mit Fehlern ist sehr klein im Vergleich zu der Anzahl der Zeilen ohne Fehler, deshalb würde ich alle Zeilen löschen, wo es Fehler gibt.
<br><br>




