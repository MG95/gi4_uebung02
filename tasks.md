A 1 a
--
Einbindung der Systemlibraries, also in der #include <NAME> Notation, ist nicht notwendig, da der Compiler die Abhängigkeiten in den Systemordnern sucht (zB /usr/local/include), oder ueber den mit -l FLAG angegeben Ordner einbindet. (UNIX)

A 1 c
--
Es muss die input.o Datei als Abhängigkeit der main.c deklariert werden, damit MAKE die Abhängigkeiten korrekt auflösen kann.