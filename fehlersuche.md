Ich habe das Programm gestartet und 55 eingegeben und dann crash das Programm. Dann bin ich in das
Program.cs und habe dort den Code angeschaut. Der Input der Column wird zu einer Zahl geparst und direkt
in die MakeMove Methode reingegeben. Wenn man einen Buchstaben, eine ungültige Zahl oder eine leere Eingabe 
reingibt, dann crasht das Programm. Das Programm crasht auch, wenn eine Column schon voll ist.

Lösung: Zwei If's machen. Beim Ersten überprüfen, ob es eine gültige column Nummer bzw. Eingabe isT. Beim Zweiten if überprüfen, ob colum
schon voll ist --> MakeMove gibt -1 zurück wenn eine column voll ist.

Testprotokoll geschrieben nach Änderungen und für die neu hinzugefügten Tests. 
