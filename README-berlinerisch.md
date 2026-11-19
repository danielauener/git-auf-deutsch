# Git uff Berlinerisch

Na, wat kiekste? Die täjliche Quatscherei in deutschen Entwicklerbuden, die `git`
(übersetzt: `Schwachkopp` oder `Flitzpiepe`) benutzen, is meistens dit feinste Denglisch.
_"Kannste ma eben pullen?"_ oder _"Haste dit jepusht?"_ sind nur zwee von die Dinger,
wo eem die Ohren bei klingeln.

Git uff Berlinerisch schafft da Abhilfe. Dit is Berlin, wa!

## Ick sach ma so

Hier kommen zwee Tabellen mit Wörtern für'n Alltach.

| Wat de machst | Wie de jetz quatschst | Wie de dit sagen solltest |
|---------------|-----------------------|---------------------------|
| init          | initten               | uffmachen                 |
| add           | adden                 | rinpacken                 |
| blame         | blamen                | anpflaumen                |
| pull          | pullen                | ranziehn                  |
| push          | pushen                | rüberschubsen             |
| clone         | clonen                | abkieken                  |
| fetch         | fetchen               | nachkieken                |
| branch        | branchen              | abbiegen                  |
| commit        | commiten              | bongen                    |
| rebase        | rebasen               | umziehn                   |
| diff          | diffen                | vajleichen                |
| merge         | mergen                | rindamit                  |
| fork          | forken                | abhaun                    |
| stash         | stashen               | verbuddeln                |
| tag           | taggen                | ansprühn                  |
| cherry-pick   | cherry-picken         | rauspuln                  |
| checkout      | auschecken            | umsteigen                 |
| squash        | squashen              | plattmachen               |

Hier noch'n paar Dinger (nich allet janz ernst jemeint, wa):

| Dit Dingens   | Wie de jetz quatschst | Wie de dit sagen solltest   |
|---------------|-----------------------|-----------------------------|
| git           | git                   | Flitzpiepe                  |
| github        | github                | Flitzpiepen-Hauptstadt      |
| gitlab        | gitlab                | Flitzpiepen-Hinterhof       |
| gitea         | gitea                 | Flitzpiepen-Plörre          |
| blame         | blame                 | Anpflaumerei                |
| bitbucket     | bitbucket             | Jebisseimer                 |
| repository    | repo                  | Kiez                        |
| branch        | branch                | Seitenflüjel                |
| commit        | commit                | Bon                         |
| log           | log                   | Kladde                      |
| pull request  | pull request          | Ziehbejehrn                 |
| merge request | merge request         | Rindamit-Antrach            |
| stash         | stash                 | Buddelkiste                 |
| status        | status                | Wat los                     |
| tag           | tag                   | Krakel                      |
| origin        | origin                | Heimatkiez                  |
| master        | master                | Meesta                      |
| main          | main                  | Vorderhaus                  |
| remote        | remote                | JWD (janz weit draußen)     |

## So redet man dit

    - Kannste den Seitenflüjel, den ick jrade umjezogen hab, ranziehn und inne Flitzpiepen-Hauptstadt rüberschubsen?

    - Dafür hab ick'n neuen Kiez uffjemacht, kiek den ab und nimm dir den Entwickler-Seitenflüjel.

    - Nee, schubs dit jleich zum Meesta im Heimatkiez!

    - Inne Anpflaumerei kannste sehn, wer dit verzapft hat.

    - Ick bin jrade abjebogen und hab den Kram aus meene Buddelkiste wieder ausjebuddelt.

    - Mach'n Ziehbejehrn, wenn de mit dem Rindamit fertich bist!

    - Am besten puln wa uns die Rosinen aus'm Vorderhaus raus.

    - Hau doch inne Flitzpiepen-Hauptstadt ab!

    - Wenn de fertich bist, kannste dit Ziehbejehrn jleich plattmachen. Und dann: rin damit!

    - Inne Flitzpiepen-Kladde kannste nachkieken, wer zuletzt'n plattjemachten Bon int Vorderhaus jeschoben hat.

    - Der Rindamit-Antrach liecht schon länger rum als'n Termin uff'm Bürjeramt.

## Flitzpiepe uff Berlinerisch benutzen

Wer jetz noch'n Schritt weiter will: Hier steht, wie de die Flitzpiepe uff Berlinerisch
in deine Konsole kriegst. Weil die Flitzpiepe keene Umlaute verträcht, müssen wa bei die
Befehle leider drauf verzichten. Pack dit hier in deine `~/.gitconfig`:

    git config --global alias.uffmachen init
    git config --global alias.abkieken clone
    git config --global alias.nachkieken fetch
    git config --global alias.ranziehn pull
    git config --global alias.rinpacken add
    git config --global alias.rueberschubsen push
    git config --global alias.schnauze 'push --force-with-lease'
    git config --global alias.abbiegen branch
    git config --global alias.seitenfluejel branch
    git config --global alias.bongen commit
    git config --global alias.umziehn rebase
    git config --global alias.vajleichen diff
    git config --global alias.rindamit merge
    git config --global alias.verbuddeln stash
    git config --global alias.anspruehn tag
    git config --global alias.rauspuln cherry-pick
    git config --global alias.umsteigen checkout
    git config --global alias.kladde log
    git config --global alias.wat-los status
    git config --global alias.anpflaumen blame
    git config --global alias.jwd remote

Wenn de dit nur in eenem Kiez haben willst, lass da drin `berlinerisch.sh` loofen.

Und schreib die folgende Zeile in deine `~/.bashrc` (oder wat dein Rechner sonst so hat):

    alias flitzpiepe=git
