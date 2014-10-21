# Git auf Deutsch (Sächsische)

De dägliche gommunigation in deutschen Endwicklungsteams, wo die `git` 
(übersetzt: `Schwachkopf`) anwenden tun, is oft das feinste Denglish. 
_"Kannste ma pulln"_ oder _"Haste jepushd"_ sin nur zwee
dor seltsam klingden ausdrügge.

Git auf deutsch (Sächsische) schafft abhilfe!

## Vorschläche

Nu folgchen zwee Tabellen mit de Vorschlechen für den tächlichen Jebrauch.

| Verb        | Aktueller Jebrauch | Vorschlach             |
|-------------|--------------------|------------------------|
| pull        | pullen             | zeern                  |
| push        | pushen             | drügggn                |
| fetch       | fetchen            | holln                   |
| branch      | branchen           | abzweijchen            |
| commit      | commiten           | überjeben              |
| rebase      | rebasen            | umschreiben            |
| merge       | mergen             | zammmeeren         |
| stash       | stashen            | indebude             |
| tag         | tagen              | markieren              |
| cherry-pick | cherry-picken      | de rosinen rausglaubm  |

| Substantiv   | Aktueller jebrauch | Vorschlach     |
|--------------|--------------------|---------------|
| git          | git                | blinse   |
| repository   | repo               | lareerstätte   |
| branch       | branch             | zweeg         |
| commit       | commit             | überjabe      |
| pull request | pull request       | nimmdasanfrache  |
| stash        | stash              | buchte      |
| tag          | tag                | margiern    |

## Beispiele

    - Kannste de den Zweeg, den ich gerade umjeschrim hawve, zern un nach github drüggn?

    - Ich hawve gerade abjezweegt und de Änderungen aus meiner buchte überjem.

    - Mache een nimmdasanfrache, wenn de mit dem zammmeeren fertch bist!

    - Am besten wir glauben uns die Rosinen aus dem Meisterzweeg heraus.

## Git auf Deutsch (Sächsisch) anwenden

Wer den nächsten Schritt machen will, hier eine Anleitung, die Git auf Deutsch
in Deine Konsole bringt. Da Git keine Umlaute zulässt, müssen wir in den 
Befehlen leider darauf verzichten. Nimm folgende Änderungen in Deiner `~/.gitconfig` 
vor:

    git config --global alias.zeern pull
    git config --global alias.druck push
    git config --global alias.zwee branch
    git config --global alias.verzweechn branch
    git config --global alias.uberjem commit
    git config --global alias.umschreim rebase
    git config --global alias.zammmeeren merge
    git config --global alias.indebude stash
    git config --global alias.margiern tag

    alias blinse=git
