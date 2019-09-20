# Aufbau einer Streaming und Analyse Umgebung für detect-hate.com

Inhalt dieses Github Repos sind die Unterlagen für meine Semesterarbeit im CAS Big Data. Darin wird der Aufbau einer Streaming und Analyse Umgebung für Tweets beschrieben:

* Abgesetzte Tweets von der Twitter API beziehen
* Unbearbeitet Tweets und Metainformationen in einer Datenbank persistenten um für die Matserarbeit Trainingsdaten zur Verfügung zu haben. Mit diesen Daten sollen spu ̈ter die Machine Leaerning Modell von trainiert werden.
* Datenaufbereitung der von Twitter bezogenen Daten
* Hasskommentare in Tweets erkennen, mittels der detect-hate App (www.detect-hate.com) klassifizieren
* Tweets und Prognose der Modelle persitieren
* Dashboard mit den Resultaten erstellen
* Installation auf dem [nHex3 Big Data Cluster](http://bigboards.io/orderprototype/)
