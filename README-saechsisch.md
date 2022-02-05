# Git off Deidsch (Säggssch)

Die däschlische Gommunigation in deidschen Endwiglungsdiehms, in den `git` 
(iebersetzt: `Blinse`) eigesetzt werd, is sehr oft Denglisch. 
Dobei kommd ofd merkgwerdsches Zeich wie _"Kannsde ma bulln?"_ oder
_"Hasde gebuschd?"_ raus.

Git off Deidsch (Säggssch) ziehd de Karre ausm Mist!

## Vorschläsche

Nu folschen zwee Dabelln mit Vorschläschen für den däschlischen Gebrauch.

| Verb        | Denglischer Mist   | Vorschlach             |
|-------------|--------------------|------------------------|
| pull        | pullen             | zerrn                  |
| push        | pushen             | driggn                 |
| fetch       | fetchen            | holn                   |
| branch      | branchen           | abzweeschen            |
| commit      | commiten           | iebergehm              |
| rebase      | rebasen            | umschreihm             |
| merge       | mergen             | zammmeern              |
| stash       | stashen            | in de Buchde schdelln  |
| tag         | taggen             | margiern               |
| cherry-pick | cherry-picken      | de Rosinen rausglaum   |

| Subsdandiv   | Denglischer Mist   | Vorschlach        |
|--------------|--------------------|-------------------|
| git          | git                | Blinse            |
| repository   | repo               | Laacherschdädde   |
| branch       | branch             | Zweesch           |
| commit       | commit             | Iebergabe         |
| pull request | pull request       | Nimmdasanfrache   |
| stash        | stash              | Buchde            |
| tag          | tag                | Margierer         |

## Beispiele

    - Isch hab den Zweesch grad umgeschriehm, kannsde den zerrn unn off de Blinsennabe driggn?

    - Isch hab grade abgezweescht und de Änderung aus meiner Buchde iebergehm.

    - Mach eene Nimmdasanfrache, wenn de mit dem Zammmeern fertsch bist!

    - Am besten mier glaum uns de Rosin ausm Meesterzweesch.

## Git off Säggssch off dr Konsole

Wennde den näschsdn Schridd machn willsd, folsche dr Anleidung um de Blinse ooch off
dr Konsole off Säggssch zu benudzn.

De Blinse kann ned mid Umlauden umgehn, weil's ehm enne Blinse is. Äs unn Ös gehn also
ned. Genuch Gelapp, nu fieschsde das in deene `~/.gitconfig` ein:

    git config --global alias.zerrn pull
    git config --global alias.driggn push
    git config --global alias.zweesch branch
    git config --global alias.abzweeschen branch
    git config --global alias.iebergehm commit
    git config --global alias.iebergabe commit
    git config --global alias.umschreihm rebase
    git config --global alias.zammmeern merge
    git config --global alias.indebuchde stash
    git config --global alias.buchde stash
    git config --global alias.margiern tag
    git config --global alias.margierer tag

    alias blinse=git
