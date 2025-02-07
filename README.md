[![CC BY-SA 4.0][cc-by-sa-shield]][cc-by-sa]   

This work is licensed under a
[Creative Commons Attribution-ShareAlike 4.0 International License][cc-by-sa].

[cc-by-sa]: http://creativecommons.org/licenses/by-sa/4.0/
[cc-by-sa-image]: https://licensebuttons.net/l/by-sa/4.0/88x31.png
[cc-by-sa-shield]: https://img.shields.io/badge/License-CC%20BY--SA%204.0-lightgrey.svg

# Vorwort

Dies ist das Vorlesungsskript meiner Vorlesung ’Aufbau der Materie I’.
Sie ist eine Kursvorlesung für Lehramts-Studierende im dritten Jahr des
Bachelorstudiums. Bei der Auswahl und Gewichtung der Themen folgt sie
sehr stark dem in Bayreuth Üblichen.

Neben dem Skript gibt es zu jedem Kapitel insgesamt circa eine Stunde
’Vorlesung’ auf [Video](https://mms.uni-bayreuth.de/Panopto/Pages/Sessions/List.aspx?folderID=67075f81-052d-4361-8090-b27d00f5e207),
in der ich mündlich durch den Text führe und dabei an den Rand kritzle.
Ich habe den Eindruck, dass es mir beim Sprechen leichter fällt, die
Dinge in einen Zusammenhang zu bringen als beim Schreiben, da ich mich
traue, schlampiger zu sein. Zur Vorbereitung gab es dann noch ein online
multiple-choice Quiz. Im Plenum besprechen wir offene Fragen und
diskutierten Aufgaben ähnlich zu [Eric Mazurs ConcepTests](https://mazur.harvard.edu/research-areas/peer-instruction).
Schließlich gibt es die in der Physik üblichen Übungszettel und
Kleingruppen-Übungen. Manche Beispiele benutzen
[Julia](https://julialang.org/) und
[Pluto](https://github.com/fonsp/Pluto.jl).

Dieses Skript ist ’work in progress’, und wahrscheinlich nie wirklich
fertig. Es beruht zum Teil auf meinem [Skript zur Molekülphysik](https://github.com/Lippitz-Lab/Molekuele-und-Festkoerper).
Trotzdem wird es noch Fehler enthalten. Wenn Sie Fehler finden, sagen
Sie es mir bitte. Die aktuellste Version des Vorlesungsskripts finden
Sie [hier](https://github.com/Lippitz-Lab/EPM1). Ich habe
alles unter eine CC-BY-SA-Lizenz gestellt (siehe Fußzeile). In meinen
Worten: Sie können damit machen, was Sie wollen. Wenn Sie Ihre Arbeit
der Öffentlichkeit zur Verfügung stellen, erwähnen Sie mich und
verwenden Sie eine ähnliche Lizenz.

Der Text wurde mit der LaTeX-Klasse [’tufte-book’](https://tufte-latex.github.io/tufte-latex/)von Bil Kleb, Bill Wood
und Kevin Godby gesetzt, die sich der Arbeit von [Edward Tufte](https://www.edwardtufte.com/) annähert. Ich habe
viele der Modifikationen angewandt, die von Dirk Eddelbüttel im R-Paket
’tint’ ([tint: tint is not
Tufte](https://dirk.eddelbuettel.com/code/tint.html)) eingeführt wurden. Die Quelle ist
vorerst LaTeX, nicht Markdown.


## Struktur des Repositorys

Die Kapitel sind einzelne TeX-Dateien im Verzeichnisbaum, die per 'include' in die Haupt-TeX-Datei eingefügt werden. Die Abbildungen werden meist mit tikz erstellt. Tikz-external wird verwendet, um Kompilierungszeit zu sparen. Es generiert die pdfs im Verzeichnis 'tikz_external'. 

