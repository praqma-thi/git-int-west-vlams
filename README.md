# Git int west-vlams

## Introdukshe

't Is tid dam kje deftig vlams kunn klapn in nuzn industrie. Da moe gedoan zin
va te klapn over branchn te pushn en commits ut the checkn. Ti doavoorn dak ier 
e boeln aliasn en tope gesmeetn dam et dagelijks gebruk va `git` (`kloot`) were 
wa beter kun doen boegeern in 't plat west-vlams.


## Vervangingn

Ier ej ne poar tabelln met werkwoordn en substantievn daj in 't doagelijkshe
gebrukt, me suggesties vo vervaningn int plat west-vlams. Oj betere et, lat me
weetn, ksmitn ze der geirn bie.

| Werkwoord   | Hudig gebruk   | Vervaning     |
|-------------|----------------|---------------|
| init        | init           | begunt        |
| clone       | clonet         | kloont        |
| pull        | pullt          | trekt         |
| push        | pusht          | duwt          |
| fetch       | fetcht         | oalt          |
| switch      | switcht        |               |
| checkout    | checkt ut      | pakt          |
| branch      | brancht        |               |
| add         | add            |               |
| commit      | commit         | ontout        |
| tag         | tagt           |               |
| rebase      | rebaset        | versmit       |
| merge       | merget         | mingelt       |
| stash       | stasht         |               |
| cherry-pick | cherry-pickt   | muggezift     |
| blame       | blamet         | beschuldigt   |
| log	      | logt           | erinnert      |
| revert      | revert         | kjerrekewere  |

| Substantief  | Hudig gebruk   | Vervaning    |
|--------------|----------------|--------------|
| git          | git            | kloot        |
| repository   | repo           | oop          |
| branch       | branch         | stok         |
| commit       | commit         | brokke       |
| tag          | tag            |              |
| pull request | pull request   |              |
| stash        | stash          |              |
| head         | head           | kop          |
| remote       | remote         | elders       |
| origin       | origin         | thuzent      |
| main         | main           |              |


## Vorbeeldn

    - Trekt me stok ekje en duwtn na GitHub.

    - Oj je stok versmit volgt je kop.

    - Ontout je werk en duwt de brokke na thuzent.

    - Erinnert ekje dam kun zien wukke brokke dam moen muggeziftn.

    - Kloont den oop van elders en beschuldigt kje die latste poar brokkn.

    - Die laste brokke wa nie zuver, kjerrekewere en duwt upnieuw.

    - ...


## Vorbeeld commandos

```bash
# git init
kloot begunt

# git add test.py
kloot add test.py

# git commit -m "Add new features"
kloot ontout -m "Nieuwn brol"

# git remote add origin
kloot elders add thuzent

# git push origin main
kloot duwt thuzent main

# git fetch origin
kloot oalt thuzent

# git pull origin
kloot trekt thuzent

# git merge origin/main
kloot mingelt thuzent/main
```


## Doagelijks gebruk

Vo 't gemakkelijkr te moakn ek ier ne boel aliasn daj mor ij `~/.gitconfig` moe
smitn vor over te schoakeln na de west-vlamshe vervangingn.

```bash
git config --global alias.begunt init
git config --global alias.kloont clone
git config --global alias.trekt pull
git config --global alias.duwt push
git config --global alias.forceert "push --force"
git config --global alias.oalt fetch
git config --global alias.switch switch
git config --global alias.pakt checkout
git config --global alias.branch branch
git config --global alias.add add
git config --global alias.ontout commit
git config --global alias.versmit rebase
git config --global alias.mingelt merge
git config --global alias.stash stash
git config --global alias.cherry-pick cherry-pick
git config --global alias.beschuldigt blame
git config --global alias.erinnert log
git config --global alias.elders remote

alias kloot=git
```
