# AmbiLIGHT
Programmierung:
	1. Öffne diesen Arduino Code
	
	2. Ändere nun die Anzahl der LEDs und den Daten Pin
	

	3. Wenn du kein Netz-Teil anbauen möchtest kannst du auch diese Zeile Ändern
	
	Bei einem USB 3.0 Anschluss kannst du es so lassen.
	Bei USB 2.0 must du 500 statt 900 angeben.
	Bei USB 1.0 auch 500 statt 900. 

	4. Nun kommen wir zum herunterladen der Bibliothek 
	• Gehe auf Sketch
	
	• Bibliothek einbinden
	• Bibliotheken verwalten
	• Und suche dort nach FastLED
	
	• Und gehe auf Installieren
	
	5. Wenn du alles gemacht hast kannst du nun das Programm auf den Arduino laden.
	
	
	
Fehler die Auftreten können:
	Wenn das Programm NICHT auf den Arduino geladen werden kann hilft vielleicht dies:

	1. Gehe auf Werkzeuge
	
	
	2. Ändere das Board auf den Arduino Nano
	
	3. Ändere auch den Prozessor auf den Atmega328P (Old Bootloader)

	4. Prüfe ob der angeschlossener USB Port richtig eingestellt ist. (Dies kannst du über den Reiter "Port" ändern.
