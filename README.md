# Git auf Deutsch

Die tägliche Kommunikation in deutschen Entwicklungsteams, die `git`
(übersetzt: `Schwachkopf` oder `Depp`) anwenden, ist oft das feinste Denglish.
_"Kannst du bitte pullen"_ oder _"Hast du gepusht"_ sind nur zwei
der oft seltsam klingenden Konstruktionen.

Git auf Deutsch schafft Abhilfe!

## Vorschläge

Es folgen zwei Tabellen mit Vorschlägen für den täglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | eröffnen              |
| add         | adden              | hinzufügen            |
| blame       | blamen             | beschuldigen          |
| pull        | pullen             | ziehen                |
| push        | pushen             | schieben              |
| clone       | clonen             | nachmachen            |
| fetch       | fetchen            | holen                 |
| branch      | branchen           | abzweigen             |
| commit      | commiten           | einbuchen             |
| rebase      | rebasen            | (neu) erden           |
| diff        | diffen             | unterscheiden         |
| merge       | mergen             | zusammenführen        |
| fork        | forken             | gabeln                |
| stash       | stashen            | verstauen             |
| tag         | taggen             | markieren             |
| cherry-pick | cherry-picken      | Rosinen herauspicken  |
| checkout    | checkouten         | ausbuchen             |
| squash      | squashen           | quetschen             |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Depp                       |
| github        | github             | Deppenzentrum              |
| gitlab        | gitlab             | Deppenlabor                |
| gitea         | gitea              | Deppentee                  |
| blame         | blame              | Beschuldigung              |
| bitbucket     | bitbucket          | Gebisseimer                |
| repository    | repo               | Depot                      |
| branch        | branch             | Zweig                      |
| commit        | commit             | Einbuchung                 |
| log           | log                | Tagebuch                   |
| pull request  | pull request       | Ziehbegehren               |
| merge request | merge request      | Antrag auf Zusammenführung |
| stash         | stash              | Versteck                   |
| status        | status             | Zustand                    |
| tag           | tag                | Markierung                 |
| origin        | origin             | Ursprung                   |
| master        | master             | Meister                    |
| main          | main               | Haupt                      |

## Beispiele

    - Kannst du den Zweig, den ich gerade umgeschrieben hab, ziehen und zum Deppenzentrum drücken?

    - Dafür habe ich ein neues Depot eröffnet, mach sie nach und nimm dir den Entwicklungszweig.

    - Nein, drücke das gleich zum Meister im Ursprung!
    
    - Du kannst in der Deppenbeschuldigung sehen, wer das geändert hat.

    - Ich hab gerade abgezweigt und die Änderungen aus meinem Versteck übergeben.

    - Mach ein Ziehbegehren, wenn du mit der Vereinigung fertig bist!

    - Am besten wir picken uns die Rosinen aus dem Hauptzweig heraus.

    - Gabeln Sie im Deppenzentrum!
    
    - Wenn du fertig bist, dann kannst du das Ziehbegehren sofort quetschen und zusammenführen.
    
    - Im Deppentagebuch kannst du nachlesen, wer zuletzt eine gequetschte Einbuchung zusammengeführt hat.

## Depp auf Deutsch anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Depp auf Deutsch in Deine Konsole bringt. Da Depp keine Umlaute zulässt, müssen wir in den Befehlen leider darauf verzichten. Nimm folgende Änderungen in deiner `~/.gitconfig` vor:

    git config --global alias.eroeffne init
    git config --global alias.machnach clone
    git config --global alias.zieh pull
    git config --global alias.fueghinzu add
    git config --global alias.drueck push
    git config --global alias.pfusch 'push --force'
    git config --global alias.zweig branch
    git config --global alias.verzweige branch
    git config --global alias.buche-ein commit
    git config --global alias.erde rebase
    git config --global alias.unterscheide diff
    git config --global alias.vereinige merge
    git config --global alias.bunkere stash
    git config --global alias.markiere tag
    git config --global alias.buche-aus checkout
    git config --global alias.tagebuch log
    git config --global alias.zustand status
    git config --global alias.beschuldige blame

Und füge die folgende Zeile zu deiner `~/.bashrc` (oder das Äquivalent auf deinem Betriebssystem) hinzu:

    alias depp=git
https://github.com/danielauener/git-auf-deutsch.git
