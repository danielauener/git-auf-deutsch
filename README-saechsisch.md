# Git auf Deutsch (Säggssch)

Die däschliche Gommunigation in deudschen Endwiglungsteams, in den `git` 
(ibersetzt: `Blinse`) eigesetzt werd, is sehr oft Denglish. 
_"Kannste ma bulln"_ oder _"Haste gebuschd"_ sin nur zwee
dor seltsam klingden Ausdrigge.

Git off Deudsch (Säggssch) ziehd die Karre ausm Mist!

## Vorschläsche

Nu folschen zwee Dabelln mit Vorschläschen fürn däglichen Gebrauch.

| Verb        | Aktueller Gebrauch | Vorschlach             |
|-------------|--------------------|------------------------|
| pull        | pullen             | zerrn                  |
| push        | pushen             | driggn                 |
| fetch       | fetchen            | holln                  |
| branch      | branchen           | abzweijschen           |
| commit      | commiten           | iebergehm              |
| rebase      | rebasen            | umschreihm             |
| merge       | mergen             | zammmeern              |
| stash       | stashen            | indebuchdeschdelln     |
| tag         | tagen              | margiern               |
| cherry-pick | cherry-picken      | de Rosinen rausglaum   |

| Substantiv   | Aktueller Gebrauch | Vorschlach        |
|--------------|--------------------|-------------------|
| git          | git                | Blinse            |
| repository   | repo               | Laacherschdädde   |
| branch       | branch             | Zweesch           |
| commit       | commit             | Iebergabe         |
| pull request | pull request       | Nimmdasanfrache   |
| stash        | stash              | Buchde            |
| tag          | tag                | Margierer         |

## Beispiele

    - Kannste de den Zweesch, den ich gerade umgeschriem hab, zerrn un zu Github drüggn?

    - Isch hab grade abgezweescht und de Änderung aus meiner Buchde iebergehm.

    - Mach eene Nimmdasanfrache, wenn de mit dem Zammmeeren fertsch bist!

    - Am besten mier glaum uns de Rosin ausm Meisterzweesch.

## Git off Deutsch (Säggssch) anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf Deutsch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den 
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig` 
vor:

    git config --global alias.zerrn pull
    git config --global alias.driggn push
    git config --global alias.zweesch branch
    git config --global alias.abzweijschen branch
    git config --global alias.iebergehm commit
    git config --global alias.iebergabe commit
    git config --global alias.umschreim rebase
    git config --global alias.zammmeern merge
    git config --global alias.indebuchde stash
    git config --global alias.buchde stash
    git config --global alias.margiern tag
    git config --global alias.margierer tag

    alias blinse=git
