# Datenschutzerklärung: easyBasar POS Toolkit

Stand: 19. Oktober 2026

Das easyBasar POS Toolkit ist eine Browser Erweiterung für Google Chrome, die vom Ski Club Rötteln e.V. für die Organisation des eigenen Skibasars mit der Plattform easyBasar (www.easybasar.de) entwickelt wird. Die Erweiterung ist nicht gelistet und wird nur per Link an die Helfer des Vereins verteilt.

## Welche Daten die Erweiterung verarbeitet

Die Erweiterung läuft ausschließlich auf Seiten von easybasar.de. Dort liest sie den Inhalt der Seite (Artikel, Verkäufer, Preise, Formulare) und schreibt Eingaben der Helfer in die Formulare der Seite, genau so, als würden die Helfer die Seite von Hand bedienen. Für den Wechsel des Verkäufers, das Laden von Artikellisten und das Auschecken von Artikeln ruft die Erweiterung dieselben Schnittstellen von easybasar.de auf, die die Seite selbst benutzt, mit der bestehenden Anmeldung des Helfers.

Lokal im Browser (chrome.storage.local) speichert die Erweiterung:

* Einstellungen der Erweiterung (welche Module aktiv sind, Testmodus, Kachelkonfiguration)
* die Zuordnung von Händler Etikettencodes zu easyBasar Artikelnummern
* Arbeitshilfen: welche Etiketten gedruckt wurden, der Fortschritt eines laufenden Excel Imports und die zuletzt erfassten Artikel

Beim Excel Import wird die gewählte Datei nur im Browser gelesen und nicht hochgeladen.

## Was die Erweiterung nicht tut

* Sie überträgt keine Daten an den Entwickler, den Verein oder Dritte. Es gibt keinen eigenen Server.
* Sie liest keine anderen Webseiten, keinen Browserverlauf und keine Passwörter.
* Sie legt keine Konten an und meldet niemanden an oder ab.
* Sie enthält keine Werbung, keine Analyse Dienste und keinen aus dem Internet nachgeladenen Code.

## Berechtigungen

* `storage`: zum Speichern der oben genannten Einstellungen und Arbeitshilfen im Browser.
* Zugriff auf `https://www.easybasar.de/*` und `https://easybasar.de/*`: damit die Erweiterung dort ihre Oberfläche anzeigen und die Formulare bedienen kann. Auf anderen Seiten ist sie nicht aktiv.

## Löschen der Daten

Alle lokal gespeicherten Daten werden mit dem Entfernen der Erweiterung aus Chrome gelöscht. Einzelne Daten lassen sich vorher in den Einstellungen der Erweiterung zurücksetzen.

## Verantwortlich

Ski Club Rötteln e.V., IT und Skibasar
Kontakt: jonas@jonasschwarzwaelder.com
