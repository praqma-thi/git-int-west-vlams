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
| init        | initn          | begunt        |
| clone       | clonen         | kloont        |
| pull        | pulln          | trekt         |
| push        | pushn          | duwt          |
| fetch       | fetchn         | pakt          |
| switch      | switch         | verandert     |
| checkout    | utcheckn       |               |
| branch      | branchn        |               |
| add         | addn           |               |
| commit      | commitn        |               |
| rebase      | rebasen        | versmit       |
| merge       | mergen         |               |
| stash       | stashn         |               |
| cherry-pick | cherry-pickn   |               |
| blame       | blamen         |               |
| log	      | loggn          |               |
| revert      | revertn        | kjerrekewere  |

| Substantief  | Hudig gebruk   | Vervaning    |
|--------------|----------------|--------------|
| git          | git            | kloot        |
| repository   | repo           |              |
| branch       | branch         | stok         |
| commit       | commit         |              |
| pull request | pull request   |              |
| stash        | stash          |              |
| head         | head           | tote         |
| remote       | remote         |              |
| origin       | origin         | thuzent      |
| main         | main           |              |


## Vorbeeldn

    - Trekt me stok ekje en duwtn na GitHub

    - Pakt eerst van thuzent vo daj duwt

    - Errinnert, oj je stok versmit volgt je tote

    - ...

## Vorbeeld commandos

```bash
# git init
kloot begunt

# git add test.py
kloot add test.py

# git commit -m "Add new features"
kloot commit -m "Nieuwn brol"

# git remote add origin
kloot remote add thuzent

# git push origin main
kloot duwt thuzent main

# git fetch origin
kloot pakt thuzent

# git pull origin
kloot trekt thuzent

# git merge origin/main
kloot merge thuzent/main
```

## Doagelijks gebruk

Vo 't gemakkelijkr te moakn ek ier ne boel aliasn daj mor ij `~/.gitconfig` moe
smitn vor over te schoakeln na de west-vlamshe vervangingn.

```bash
git config --global alias.begunt init
git config --global alias.kloont clone
git config --global alias.trekt pull
git config --global alias.duwt push
git config --global alias._____ "push --force"
git config --global alias.pakt fetch
git config --global alias.verandert switch
git config --global alias.checkout checkout
git config --global alias.branch branch
git config --global alias.add add
git config --global alias.commit commit
git config --global alias.versmit rebase
git config --global alias.merge merge
git config --global alias.stash stash
git config --global alias.cherry-pick cherry-pick
git config --global alias.blame blame
git config --global alias.log log

alias kloot=git
```
