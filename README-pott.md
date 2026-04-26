# Git auf Pott

Glückauf! Die tägliche Quasselei in deutschen Entwickler-Butzen, die `git`
(übersetzt: `Schwachkopf` oder `Depp`) anwenden, ist oft das feinste Denglish.
_"Kannse ma eben pullen"_ oder _"Hasse dat getz gepusht"_ sind da nur zwei
vonne Dinger, die sich schräg inne Ohren anhören.

Git auf Pott schafft da Abhilfe, weisse Bescheid!

## Tacheles

Hier kommen getz zwei Schichtpläne mit Begriffe, die de jeden Tag bei de Maloche gebrauchen kannse.

| Dat Tun     | Wie man getz quasselt | Watt de besser sagn kannse |
|-------------|-----------------------|----------------------------|
| init        | initten               | anstechen                  |
| add         | adden                 | aufladen                   |
| blame       | blamen                | ankacken                   |
| pull        | pullen                | einfahren                  |
| push        | pushen                | hochjagen                  |
| clone       | clonen                | abkupfern                  |
| fetch       | fetchen               | nachkucken                 |
| branch      | branchen              | abknicken                  |
| commit      | commiten              | festkloppen                |
| rebase      | rebasen               | umpfropfen                 |
| diff        | diffen                | lünkern                    |
| merge       | mergen                | zusammenkloppen            |
| fork        | forken                | abzwacken                  |
| stash       | stashen               | beiseiteschaffen           |
| tag         | taggen                | bekleben                   |
| cherry-pick | cherry-picken         | rauspicken                 |
| checkout    | checkouten            | rüberspringen              |
| squash      | squashen              | stauchen                   |

Hier noch n’ paar Dinger (manche davon nich ganz ernst gemeint, weisse Bescheid):

| Dat Ding      | Wie man getz quasselt | Watt de besser sagn kannse |
|---------------|-----------------------|----------------------------|
| git           | git                   | Dussel                     |
| github        | github                | Dussel-Bude                |
| gitlab        | gitlab                | Dussel-Küche               |
| gitea         | gitea                 | Dussel-Plempe              |
| blame         | blame                 | Anschiss                   |
| bitbucket     | bitbucket             | Gebiss-Kübel               |
| repository    | repo                  | Dat Pütt                   |
| branch        | branch                | Seitenstollen              |
| commit        | commit                | Klopper                    |
| log           | log                   | Berichtsheft               |
| pull request  | pull request          | Beikipp-Frage             |
| merge request | merge request         | Zusammenklopp-Antrag       |
| stash         | stash                 | Bunker                     |
| status        | status                | Lage                       |
| tag           | tag                   | Papper                     |
| origin        | origin                | Mutterflöz                 |
| master        | master                | Vatterstollen              |
| main          | main                  | Hauptstollen               |

## So geht dat

    - Kannse den Seitenstollen, den ich gerade umgepfropft hab, einfahren und zur Dussel-Bude hochjagen?

    - Dafür hab ich dat Pütt neu angestochen, kupfer dat mal ab und schnapp dir den Malocher-Seitenstollen.

    - Nee, jag dat direkt zum Vatterstollen ins Mutterflöz!“

    - Kannse im Dussel-Anschiss kucken, wer dat verbrochen hat.

    - Ich bin gerade abgeknickt und hab den Kram aus’m Bunker wieder ausgegraben.

    - Schick ’ne Beikipp-Frage, wenn de mit’m Zusammenkloppen fertig bis’!

    - Am besten picken wir uns die dicken Brocken aus’m Hauptstollen raus.

    - Zwack dir dat mal in de Dussel-Bude ab!

    - Wenn de fertig bis’, kannse die Beikipp-Frage direkt stauchen und zusammenkloppen.

    - Im Dussel-Berichtsheft kannse nachkucken, wer zuletzt 'nen gestauchten Klopper zusammengekloppt hat.

## Dussel auf Pöttisch malochen

Wer getz den nächsten Schlag tun will, hier is der Plan, wie de dir den Dussel auf Pöttisch inne Konsole holse. Weil der Dussel aber keine Umlaute verträgt, müssen wir bei de Befehle leider drauf verzichten. Klopp folgende Änderungen in deine ~/.gitconfig rein:

    git config --global alias.anstechen init
    git config --global alias.abkupfern clone
    git config --global alias.einfahren pull
    git config --global alias.aufladen add
    git config --global alias.hochjagen push
    git config --global alias.gib-ihm 'push --force'
    git config --global alias.kick-ab branch
    git config --global alias.stollen branch
    git config --global alias.klopp-fest commit
    git config --global alias.pfropf-um rebase
    git config --global alias.luenkern diff
    git config --global alias.klopp-zusammen merge
    git config --global alias.bunkern stash
    git config --global alias.papp-drauf tag
    git config --global alias.spring-rueber checkout
    git config --global alias.berichtsheft log
    git config --global alias.lage status
    git config --global alias.kack-an blame

Und pack die folgende Zeile noch in deine ~/.bashrc (oder watt de sonst so auffe Schicht am Rechner nutzt) mit bei:

    alias dussel=git
<https://github.com/danielauener/git-auf-deutsch.git>
