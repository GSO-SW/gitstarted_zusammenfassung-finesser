# gitStarted Zusammenfassung
In diesem Repo soll zusammengefasst werden, was man für die Arbeit mit git und gitHub kennen sollte.
- In [diesem cheatsheet](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) finden Sie Hinweise, wie man .md-Dateien formatiert.
- Mit diesen [Generator](https://www.tablesgenerator.com/markdown_tables) können Sie Tabellen für Markdown erzeugen

:dart: Ziele:
1. Die Arbeit soll nicht im Browser stattfinden. Clonen Sie das Repo und arbeiten Sie lokal.
1. Hier gehts um Teamwork: Ich erwarte häufige Commits (+ häufiges pushen/pullen )

## TODO

#Begriffe definieren und erklären (z.B. repository, branch etc.)
-Repository	: In ein Repository bzw. einem Repo befinden sich alle Dateien inklusive derer vorangegangenen Versionen. Dadurch stehen stets alle Änderungen zur Verfügung, die von einer Datei ins Repo gespielt wurden und es kann nachvollzogen werden Wer, Wann, welche Änderungen durchgeführt hat.
-Branch		:Beim Einsatz von Git dienen Branches (engl.: to branch - sich verzweigen) dazu, um einen separaten Arbeitszweig zu erstellen. Dieser kann dann auch als neuer Kontext gesehen werden, in dem gearbeitet wird.
-Master		:Die Standardbezeichnung für einen Branch bei Git lautet master . Wenn Sie damit beginnen, Commits durchzuführen, erhalten Sie einen master Branch, der auf den letzten Commit zeigt, den Sie gemacht haben.
-Staging Area:Die Staging-Area ist in der Regel eine Datei, die sich in Ihrem Git-Verzeichnis befindet und Informationen darüber speichert, was in Ihren nächsten Commit einfließen soll.
-Working Dire:Das Arbeitsverzeichnis von Git (in anderen Systemen manchmal auch Sandbox oder Checkout genannt). Hier nehmen Sie alle Modifikationen am Quellcode vor. Oft findet man dafür auch die Bezeichnung Working Directory.
-HEAD		:Eine symbolische Referenz auf den neuesten Commit im aktuellen Branch. Von dieser Referenz hängt ab, welche Dateien Sie im Working Tree zur Bearbeitung vorfinden. Es handelt sich also um den „Kopf“ bzw. die Spitze eines Entwicklungsstrangs.


#git Befehle für die Arbeit mit lokalen Repositories (inkl. Erläuterungen)
-git init: erstellt ein neues Repository
-git add: fügt Veränderungen einer oder mehreren Dateien/Ordner von der working area in die staging area hinzu
-git commit (-m "message"): erstellt eine neue Version einer oder mehreren Dateien/Ordner im Repository
-git branch (name): erstellt einen neuen Branch (Namensschild -> zeigt auf einen Commit)
-git merge: führt zwei verschiedene commits zusammen
-git checkout (commitname): springt zum commit (Zeitpunkt der Version im Repository)


#git Befehle für die Arbeit mit entfernten Repositories (inkl. Erläuterungen)
-git clone <url>: Klont bzw. kopiert ein Repository in ein neu erzeugtes Verzeichnis
-git push: Benutzt man um Inhalte aus einem lokalen Repo in ein Remote-Repository hochzuladen. Man überträgt also alle commits
-git fetch: Erlaubt es Änderungen aus einem enfernten Repository in das lokale abzulegen
-git merge: Dadurch integriert man die Änderungen in das Repository
-git pull: Man kann damit die Änderungen aus einem enfernten Repo abholen und mit dem eigenen Workspace bzw. den Dateien an denen man gerade arbeitet synchronisieren. Kurz gesagt: git pull: git fetch + git merge


## TODO2
- Fachbegriffe OOP erklären (mit Beispielen)
  - abstract (Klassen)
  Als Abstrakte Klasse wird eine Klasse bezeichnet, von der keine Objekte erzeugt werden können. Diese Klassen sind nicht „vollständig“ genug, um Objekte zu instanziieren. Beispiel: Abstract Datentyp Klassenname()
  - abstract (Methoden)
  Abstrakte Methoden legen lediglich die Signatur der Methode fest, ohne sie zu implementieren. Sie sind durch das Schlüsselwort abstract gekennzeichnet und haben keinen Rumpf (Anweisungsblock). Beispiel: public Abstract Datentyp Methodenname();
  - virtual
  Bei virtual können Kinderklassen die Methode überschreiben. public virtual void Methodenname()
  - override
  Bei override werden Methoden aus der Mutterklasse überschrieben. Beispiel: public override void Methodenname()
  - Polymorphie
	bezeichnet Methodenaufrufe, mit der selben Bezeichnung, jedoch unterschiedlicher Anzahl an Übergabeparametern. 
	Das nennnt sich auch Überladung und dient dazu bei einem Konstruktoraufruf, wenn ein neues Objekt erstellt wird, beispielsweise 
	beim Hinzufügen eines Artikels in den Warenkorb ohne Angabe über die Menge, wird standardmäßig der Wert 1 verwendet. 
	Das bedeutet man hätte einen Konstruktor mit 2 Übergabeparametern und bei Auswahl der Menge, 3 Übergabeparameter.
- Wie überschreibt man die Methode `virtual string ToString()`?
public override string ToString()
    {
        TEXT;
    }

