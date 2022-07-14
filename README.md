# Tool-Supported-Data-Cleaning

## Daten Hochladen
<br>
Ich habe die Daten als CSV-Datei gespeichert und auf trifacta hochgeladen (siehe Screenshot)
<br>

![alt text](trifacta_upload.png)


1- Zuerst werden alle Zeilen gelöscht, die kein gültes Alter haben. <br>
2- Alle Zeilen ohne ID werden gelöscht. Sie könnten später manuell hinzugefügt worden sein. <br>
3- Alle Zeilen werden gelöscht, die keinen "full_name" haben. <br>
4- Alle Zeilen werden gelöscht, die keine E-Mail Adresse haben. <br>
5- Alle Zeilen werden gelöscht, die kein Gender haben. <br>
6- Um später Duplikate zu identifizieren, werden die "id" gelöscht. <br>
7- Duplikate werden gelöscht.<br> <br>

![alt text](Recipe.png)


## Ergebnis
<br>
Am Ende wurde das Ergebnis in der Datei "dsm-beuth-edl-demodata-clean.csv" gespeichert

![alt text](Clean.png)
