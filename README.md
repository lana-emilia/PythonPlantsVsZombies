# Python Plants VS Zombies
Ein einfaches PlantsVsZombies-Spiel. <br>
`Es dient nur dem persönlichen Lernen und nichtkommerziellen Gebrauch. Falls dieses Spiel das Urheberrecht verletzt, lassen Sie es mich bitte wissen.`

* Implementiere Pflanzen: Sonnenblume, Erbsenkanone, Walnuss, Schneeball-Erbsenkanone, Kirschbombe, Dreifach-Erbsenkanone, Schnapper, Puffpilz, Kartoffelmine, Dornenkraut, Angsthäschen, Kürbis, Angsthäschen, Jalapeño, Sonnenpilz, Eispilz, Hypnokraut.
* Implementiere Zombies: Zombie, Flaggenzombie, Eimerkopfzombie, Zeitungszombie.

* Verwende JSON-Dateien, um Level-Daten zu speichern (z.B. Position und Zeit der Zombies, Hintergrundinformationen).
* Unterstütze die Auswahl von Pflanzenkarten zu Beginn des Levels.
* Unterstütze Tageslevel, Nachtlevel, Level mit beweglicher Karten-Auswahl und Level mit Wall-Nuss-Bowling.

# Anforderungen
* Python 3.7
* Hinweis: Python-Version 3.7 wird empfohlen, ist jedoch nicht zwingend erforderlich. Für LINUX: Wenn Ihr Linux-System bereits Python 3+ vorinstalliert hat, können Sie dieses Spiel problemlos ausführen. Das direkte Aktualisieren auf Python 3.7 kann LINUX Mint möglicherweise beeinträchtigen.
* Python-Pygame 1.9

# Spielstart

    $ python main.py

# Spielanleitung
* Verwende die Maus, um Sonnen zu sammeln, Pflanzenkarten auszuwählen und die Pflanze zu setzen.
* Du kannst das Startlevel ändern, indem du den Wert von START_LEVEL_NUM in der Datei source/constants.py änderst.
  * Level 1 und 2: Tageslevel
  * Level 3: Nachtlevel
  * Level 4: Level mit beweglicher Karten-Auswahl
  * Level 5: Wall-Nuss-Bowling-Level

# Demo
![demo1](./demo/demo1.jpg)
