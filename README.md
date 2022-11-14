# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO
- Begriffe definieren und erklären (z.B. repository, branch etc.)
- git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
git init: erstellt ein neues Repository
git add: fügt Veränderungen einer oder mehreren Dateien/Ordner von der working area in die staging area hinzu
git commit (-m "message"): erstellt eine neue Version einer oder mehreren Dateien/Ordner im Repository
git branch (name): erstellt einen neuen Branch (Namensschild -> zeigt auf einen Commit)
git merge: führt zwei verschiedene commits zusammen
git checkout (commitname): springt zum commit (Zeitpunkt der Version im Repository)
- git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)

git clone <url>: Klont bzw. kopiert ein Repository in ein neu erzeugtes Verzeichnis
git push: 
git fetch: Erlaubt es Änderungen aus einem enfernten Repository in das lokale abzulegen
git merge: Dadurch integriert man die Änderungen in das Repository
git pull: Man kann damit die Änderungen aus einem enfernten Repo abholen und mit dem eigenen Workspace bzw. den Dateien an denen man gerade arbeitet synchronisieren. Kurz gesagt: git pull: git fetch + git merge

## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
  - abstract (Methoden)
  - virtual
  - override
  - Polymorphie
- Wie überschreibt man die Methode `virtual string ToString()`?
