# ts-client
One-Site-Application based on TypeScript

## Copyright
Copyright 2017-2022 by Maik Tizziani
Alle Dateien in diesem Repository sind gerenell Urheberrechtlich geschützt und unterliegen der GPL3.0.

Die private Nutzung und Veränderung ist generell gestattet. Copyright und Lisenzverweise müssen jedoch generell mit
übernommen werden.

Jede gewerbliche Nutzung bedarf einer gesonderten, schriftlichen Genehmigung.

Es kann vorkommen, dass bestimmte Elemente, insbesondere genutzte Bibliotheken, aber auch Teile des Sourcecodes, unter 
anderen Copyright und Lizensbestimmungen liegen. Dies ist dann in der Jeweiligen Datei oder im Dateiverzeichnis vermerkt
und muss bei Verwendung mit übernommen werden.

Für weitere Informationen zu den Lisenzbestimmungen lesen Sie bitte die [Lizensbestimmungen](LICENCE).

## Git Einstellungen

Bei einem Merge Request achtet bitte darauf, dass alle generierten Dateien und alle Projekt Dateien (IDE abhängig) zur 
.gitignore hinzugefügt werden. Das erspart einfach viel Zeit in der Nacharbeit. 

Windows Benutzer können CRLF automatisch in LF umwandeln lassen. Dies ist Allerdings kein zwang, denn einige IDE's 
zeigen dann permanent Änderungen in den Dateien an. 

    git config --global core.autocrlf true

Um beim ausschecken unter Linux und MacOS Fehlerhafte Zeilenumbrüche in Dateien zu reparieren kann man folgende
Git-Einstellung verwenden:

    git config --global core.autocrlf input