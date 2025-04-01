# Git op Kölsch

Dat daachdeechlije Klaafe bei uns Pänz en de Entwicklerbud, die `git` (op Kölsch: `Tünnes` oder `Blötschkopp`) bruche, es off dat fingste Denglisch.
"Kanns de ens trekke?" oder "Häs de geschovve?" sin nur zwei vun dä komische Saache, die mer su säht.

Git op Kölsch määt et besser!
## Vörschlääch

He sinn zwei Tabelle met Vörschlääch, die mer jede Daach bruche kann.

| Verb        | Aktueller Gebrauch | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initten            | aanfange              |
| add         | adden              | dobeidoon            |
| blame       | blamen             | bescholdije          |
| pull        | pullen             | trekke                |
| push        | pushen             | schuve              |
| clone       | clonen             | nohmaache            |
| fetch       | fetchen            | holle                 |
| branch      | branchen           | avzwieje             |
| commit      | commiten           | fessmaache             |
| rebase      | rebasen            | opfrösche          |
| diff        | diffen             | ongerscheede         |
| merge       | mergen             | zesammelege        |
| fork        | forken             | afteilche             |
| stash       | stashen            | verstoche             |
| tag         | taggen             | markeere             |
| cherry-pick | cherry-picken      | Krönche erusspöhle  |
| checkout    | checkouten         | erusnemme             |
| squash      | squashen           | plattmaache             |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktueller Gebrauch | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Tünnes                       |
| github        | github             | Tünnes-Huus              |
| gitlab        | gitlab             | Tünnes-Labor                |
| gitea         | gitea              | Tünnes-Tee                  |
| blame         | blame              | Bescholdijung              |
| bitbucket     | bitbucket          | Bess-Ämmer                |
| repository    | repo               | Spiecher                      |
| branch        | branch             | Avzweijung                      |
| commit        | commit             | Fessmaachung                 |
| log           | log                | Daachboch                   |
| pull request  | pull request       | Trekkaanfrooch               |
| merge request | merge request      | Zesammelege-Anfrooch |
| stash         | stash              | Stüffje                   |
| status        | status             | Zostand                    |
| tag           | tag                | Markeering                 |
| origin        | origin             | Oorsprong                   |
| master        | master             | Meister                    |
| main          | main               | Haupt                      |

## Beispiele

    - Kanns de dä Zweig, dän ich jraad ömgeschrevve han, trekke un zom Tünnes-Huus schuve?

    - Doför han ich e neu Lager opgemaat, maach et noh un nemm dir dä Entwicklungszweig.

    - Nä, schuv dat direkt zom Meister em Oorsprong!

    - Do kanns en de Tünnes-Bescholdijung luure, wä dat geändert hät.

    - Ich han jraad avgezweig un die Änderunge us mingem Versteck erusgehollt.

    - Maach en Trekkaanfrooch, wann de met dem Zesammelege fäädisch bes!

    - Am beste, mer pöhle uns de Krönche us däm Hauptzweig eruss.

    - Donn em Tünnes-Huus avzwieje!

    - Wann de fäädisch bes, dann kanns de de Trekkaanfrooch tirek plattmaache un zesammelege.

    - Em Tünnes-Daachboch kanns de nohkike, wä et letz en plattjemaate Fessmaachung zesammejelaat hät.

## Tünnes op Kölsch bruche

Wä noch ene Schritt wigger jon well, he en Anleitung, wie de Tünnes op Kölsch op ding Konsool kriss. Weil Tünnes kein Ömlaute kann, mösse mer en de Befehle leider drop verzichte. Donn foljende Änderunge en dinger `~/.gitconfig`:

    git config --global alias.aanfange init
    git config --global alias.nohmaache clone
    git config --global alias.trekke pull
    git config --global alias.dobeidoon add
    git config --global alias.schuve push
    git config --global alias.pfusche 'push --force'
    git config --global alias.zweig branch
    git config --global alias.avzwieje branch
    git config --global alias.fessmaache commit
    git config --global alias.opfroesche rebase
    git config --global alias.ongerscheede diff
    git config --global alias.zesammelege merge
    git config --global alias.verstoche stash
    git config --global alias.markeere tag
    git config --global alias.erusnemme checkout
    git config --global alias.daachboch log
    git config --global alias.zostand status
    git config --global alias.bescholdije blame


Un pack die Reih he noch en ding `~/.bashrc` (oder wat bei dingem System passt):
    alias tuennes=git