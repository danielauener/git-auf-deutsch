# Git uf Bärndütsch

Di täglechi Kommunikation i mundart Entwicklerteams, wo `git`
(übersetzt: `Löu` oder `Depp`) bruuche, isch öppe no vou vo Anglizisme.
_"Chasch schnäu pulle"_ oder _"Hesch scho pusht"_ si nur zwe
Byspiu vo so komische Konstruktione.

Git uf Bärndütsch ischd Rettig!

## Vorschläg

Nachfougend zwo Tabäuene mit Vorschläg füre täglech Gebruuch.

| Verb        | Aktuell Gebruuch   | Vorschlag             |
|-------------|--------------------|-----------------------|
| init        | initte             | ahfah                 |
| add         | ädde               | derzuetue             |
| blame       | blame              | ahchryde              |
| pull        | pulle              | schrysse              |
| push        | pushe              | uemoschte             |
| clone       | clone              | kopiere               |
| fetch       | fetche             | hole                  |
| branch      | branche            | vereschtle            |
| commit      | commite            | abgäh                 |
| rebase      | rebase             | zügle                 |
| diff        | diffe              | verglyche             |
| merge       | merge              | zämelege              |
| fork        | forke              | gable                 |
| stash       | stashe             | verstoue              |
| tag         | tagge              | ahstryche             |
| cherry-pick | cherry-picke       | Chriesi abläse        |
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
| commit        | commit             | Abgab                      |
| log           | log                | Tagebuech                  |
| pull request  | pull request       | Schryssahtrag              |
| merge request | merge request      | Zämelegigsahtrag           |
| stash         | stash              | Stapu                      |
| status        | status             | Zustang                    |
| tag           | tag                | Ahstrich                   |
| origin        | origin             | Ursprung                   |
| master        | master             | Meischter                  |
| main          | main               | Houpt                      |

## Beispiele

    - Chasch dr Ascht woni grad umgeschrybe ha, schrysse und i Löuverein uemoschte?

    - Für das hani es nöis Lager ahgfange, kopier ders und nimm der dr Entwicklerascht.

    - Nei, moscht das grad ue zum Meischter im Ursprung!
    
    - Das chasch ir Ahchrydig ga luege, wär das gänderet het.

    - I ha grad vereschtlet und dÄnderige usem Stapu abgäh.

    - Mach e Schryssahtrag wede mit dr Zämelegig fertig bisch!

    - Am beschte düemer vom Houptascht Chriesi abläse.

    - Gablet das ufe Chätschchübu!
    
    - Wede fertig bisch, de chasch dä Schryssahtrag grad verdrücke und zämelege.

## Löu uf Bärndütsch bruuche

Wär dr nächscht Schritt wott mache het hie none Ahleitig, wide Löu uf Bärndütsch i dini Konsole bringsch. Da Löu kener Umlut zuelaht, müessemer die bide Befäu leider usselah. Mach die folgende Änderige i dim `~/.gitconfig`:

    git config --global alias.fang-ah init
    git config --global alias.mach-nache clone
    git config --global alias.schryss pull
    git config --global alias.due-derzue add
    git config --global alias.moscht-ue push
    git config --global alias.murx-ue push --force
    git config --global alias.ascht branch
    git config --global alias.vereschtl branch
    git config --global alias.gib-ab commit
    git config --global alias.zuegu rebase
    git config --global alias.verglych diff
    git config --global alias.leg-zaeme merge
    git config --global alias.verstou stash
    git config --global alias.strych-ah tag
    git config --global alias.nimm checkout
    git config --global alias.tagebuech log
    git config --global alias.zuestang status
    git config --global alias.chryd-ah blame

Und füeg di nächsti Zyle zu dim `~/.bashrc` (oder wasimmer zglyche uf dim Betriebssystem isch) derzue:

    alias loeu=git
