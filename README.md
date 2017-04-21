# ts-client
One-Site-Application based on TypeScript


## Git Einstellungen

Bei einem Merge Request achtet bitte darauf, dass alle generierten Dateien und alle Projekt Dateien (IDE abhängig) zur 
.gitignore hinzugefügt werden. Das erspart einfach viel Zeit in der Nacharbeit. 

Windows Benutzer können CRLF automatisch in LF umwandeln lassen. Dies ist Allerdings kein zwang, denn einige IDE's 
zeigen dann permanent Änderungen in den Dateien an. 

    git config --global core.autocrlf true

Um beim ausschecken unter Linux und MacOS Fehlerhafte Zeilenumbrüche in Dateien zu reparieren kann man folgende
Git-Einstellung verwenden:

    git config --global core.autocrlf input