## Abgabe zur Bewertung (Teilprüfung 1)
: GitHub Repository Setup und Workflow 

a) GitHub Repository Setup 

1.Ich habe ein leeres Repository auf GitHub erstellt: Zuerst bin ich auf GitHub gegangen und mich mit meinem Benutzerkonto angemeldet. 
2. Danach habe ich auf das "+"-Symbol oben rechts geklickt und ein neues Repository mit dem Namen "MeinProjekt" erstellt. Das Repository habe ich als öffentliches Repository ohne README-Datei und ohne Lizenz erstellt. 

![image](https://github.com/user-attachments/assets/1feef969-c101-465f-a198-c11585f24f21)

3.Ich habe die URL des Repositories notiert: https://github.com/ArtemSkrypniak/MeinProjekt.git Diese URL werde ich später verwenden, um das Repository auf meinem lokalen Computer zu klonen. 

![image](https://github.com/user-attachments/assets/88dc5092-b911-4c61-ba89-c22f0143d3fe)

b) SSH-Schlüssel erstellen 
5.Ich habe überprüft, ob ich bereits einen SSH-Schlüssel habe: Ich habe mein Terminal Git Bash (bei Windows) geöffnet  und den folgenden Befehl ausgeführt, um zu überprüfen, ob bereits ein SSH-Schlüssel vorhanden ist:

![image](https://github.com/user-attachments/assets/d1e0c100-a3fb-4be1-980b-601dc1c984fd)


c) Lokales Repository einrichten und Workflow

8_9. Ich habe das Repository auf meinem Computer geklont: Ich habe mein Terminal geöffnet und bin in das Verzeichnis gewechselt, in dem ich das lokale Git-Repository erstellen wollte. Dann habe ich das Repository von GitHub auf meinen lokalen Rechner geklont(mit Passworteingabe). 

![image](https://github.com/user-attachments/assets/6dc22fad-bd96-4c07-bd4f-e31c8206453c)

10. Ich habe in das geklonte Verzeichnis gewechselt
11. Ich habe Git mit meinem Namen und meiner E-Mail konfiguriert

![image](https://github.com/user-attachments/assets/07b1e20c-56c1-4d5c-b10c-458b382ed7d6)

12. Ich habe eine neue Datei (main.py) erstellt und einen Initial-Commit gemacht:

![image](https://github.com/user-attachments/assets/c36e44e4-7bee-461f-bf4a-c994446dc8d5)

13. Ich habe einen neuen Branch namens "feature" erstellt.
14. Ich habe Verzeichnis und die Datei utils/database.py erstellt. Dann habe ich diese Datei zu Git hinzugefügt und einen Commit "Neue Funktion hinzugefügt" gemacht.

![image](https://github.com/user-attachments/assets/e38b6554-492d-4f46-9014-cae739ebdec4)

15. Ich habe die Datei main.py auf dem feature-Branch bearbeitet um einen Konflikt zu verursachen, wenn der Befehl „merge“ ausgegeben wird. Und führe einen Commit auf dem "feature"-Branch durch: 

![image](https://github.com/user-attachments/assets/1099e33e-a45f-49bc-8ea5-52a660bbf70e)
![image](https://github.com/user-attachments/assets/9bd660c9-275b-4b57-b641-b85b7359a083)

16. Und 17. Da das GIT-Repository auf der Website github.com erstellt wurde, existiert der master-Branch nicht. Es wird standardmäßig „main“ genannt. Daher wird Punkt 16 im „main-Branch“ ausgeführt. Ich habe auf den main-Branch gewechselt und die Datei main.py erneut bearbeitet und dasselbe Text hinzuzufugen wie in Schritt 15.

![image](https://github.com/user-attachments/assets/5aa0a492-3e56-4fa8-af2c-d4af7bd44467)

18.Ich habe versucht, den feature-Branch in den master-Branch zu mergen. In diesem Schritt ist ein Merge-Konflikt aufgetreten.
Ich habe den Merge-Konflikt manuell gelöst: In der Datei main.py gab es Markierungen, die den Konflikt anzeigten. Ich habe diese Markierungen entfernt und eine endgültige Version der Datei erstellt, indem ich die gewünschten Änderungen kombiniert habe: 
 
![image](https://github.com/user-attachments/assets/f4c43300-c8a8-41d0-b4c5-084e7cf70318)
![image](https://github.com/user-attachments/assets/c7d22aa8-2b94-48f3-a281-06291e00af1b)

Danach habe ich die Datei gespeichert, die Änderungen zu Git hinzugefügt und den Merge abgeschlossen: 
![image](https://github.com/user-attachments/assets/4c73ca28-3d1e-4da7-9a64-d5b84b171f4f)


Der nächste Schritt besteht darin, eine README-Datei zu erstellen, sie dem Repository hinzuzufügen und ein weiteres Commit hinzuzufügen.
