# Login Daten (Admin)

E-Mail-Adresse:
jeannine.doe@gmail.com

Passwort: 
Jeanninedoepassword1!


## Login Daten (kein Admin)

E-Mail-Adresse:
sam.doe@gmail.com

Passwort: 
Samdoepassword1!

(Ich habe jetzt in der Datenbank auch noch einen Account stehen gelassen, der 
mittels "soft-delete" gelöscht wurde)

### Login validiert

Hallo Marc, Fabio, Peter, 
ich habe absichtlich die Eingabe zum Login nicht serverseitig validiert. 
Da die Daten bei der Registrierung erfolgreich validiert werden, kann so 
ausgeschlossen werden, dass nicht valide Daten in die Datenbank gespeichert 
werden. Natürlich wird aber darauf validiert, ob Benutzername (E-Mail-Adresse)
und Passwirt zueinanderpassen, und auch so in der Datenbank eingetragen sind. 