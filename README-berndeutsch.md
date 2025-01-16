# Git uf Bärndütsch

Di täglechi Kommunikation i Bärner Entwicklerteams, wo `git`
(usem änglische übersetzt: `Löu` oder `Depp`) bruuche, isch vou vo Anglizisme.
_"Chasch schnäu pulle"_ oder _"Hesch scho pusht"_ si nur zwe
Byspiu vo so komische Konstrukt.

Git uf Bärndütsch isch dini Rettig!

## Vorschläg

Nachfougend zwo Tabäuene mit Vorschläg füre täglech Gebruuch.

| Verb        | Aktuell Gebruuch   | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initte             | ahfah                 |
| add         | ädde               | derzuetue             |
| blame       | blame              | ahchryde              |
| pull        | pulle              | zieh                  |
| push        | pushe              | stosse                |
| clone       | clone              | kopiere               |
| fetch       | fetche             | hole                  |
| branch      | branche            | veräschtle            |
| commit      | commite            | bueche                |
| rebase      | rebase             | zügle                 |
| diff        | diffe              | verglyche             |
| merge       | merge              | zämelege              |
| fork        | forke              | gable                 |
| stash       | stashe             | verstoue              |
| tag         | tagge              | ahstryche             |
| cherry-pick | cherry-picke       | rosine-picke          |
| checkout    | checkoute          | näh                   |
| squash      | squashe            | verdrücke             |

Hier noch einige (zum Teil nicht ganz ernste)

| Substantiv    | Aktuell Gebruuch   | Vorschlag                  |
|---------------|--------------------|----------------------------|
| git           | git                | Löu                        |
| github        | github             | Löuverein                  |
| gitlab        | gitlab             | Löulabor                   |
| gitea         | gitea              | Löugsöff                   |
| blame         | blame              | Ahchrydig                  |
| bitbucket     | bitbucket          | Chätschchübu               |
| repository    | repo               | Lager                      |
| branch        | branch             | Ascht                      |
| commit        | commit             | Buechig                    |
| log           | log                | Tagebuech                  |
| pull request  | pull request       | Ziehatrag                  |
| merge request | merge request      | Zämelegigsahtrag           |
| stash         | stash              | Stapu                      |
| status        | status             | Zuestang                    |
| tag           | tag                | Ahstrich                   |
| origin        | origin             | Ursprung                   |
| master        | master             | Meischter                  |
| main          | main               | Houpt                      |

## Beispiele

    - Chasch dr Ascht woni grad umgeschrybe ha, schrysse und i Löuverein uemoschte?

    - Für das hani es nöis Lager ahgfange, kopier ders und nimm der dr Entwicklerascht.

    - Nei, stoss das grad ue zum Meischter im Ursprung!

    - Das chasch ir Ahchrydig ga luege, wär das gänderet het.

    - I ha grad vereschtlet und d Änderige usem Stapu verbuecht.

    - Mach e Ziehahtrag wede mit dr Zämelegig fertig bisch!

    - Am beschte düemer vom Houptascht Chriesi abläse.

    - Gablet das ufe Chätschchübu!

    - Wede fertig bisch, de chasch dä Schryssahtrag grad verdrücke und zämelege.

## Löu uf Bärndütsch bruuche

Wär dr nächscht Schritt wott mache het hie none Ahleitig, wide Löu uf Bärndütsch i dini Konsole bringsch. Da Löu kener Umlut zuelaht, müessemer die bide Befäu leider usselah. Mach die folgende Änderige i dim `~/.gitconfig`:

```bash

git config --local alias.ahfah init
git config --local alias.derzuetue add
git config --local alias.ahchryde blame
git config --local alias.zieh pull
git config --local alias.stosse push
git config --local alias.kopiere clone
git config --local alias.hole fetch
git config --local alias.veraeschtle branch
git config --local alias.bueche commit
git config --local alias.zuegle rebase
git config --local alias.verglyche diff
git config --local alias.zaemelege merge
git config --local alias.gable fork
git config --local alias.verstoue stash
git config --local alias.ahstryche tag
git config --local alias.rosinepicke cherry-pick
git config --local alias.naeh checkout
git config --local alias.verdruecke squash
git config --local alias.zuestang status
```

Und füeg di nächsti Zyle zu dim `~/.bashrc` (oder wasimmer zglyche uf dim Betriebssystem isch) derzue: 
``` bash 
alias loeu=git
```