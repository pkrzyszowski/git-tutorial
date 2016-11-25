# git-tutorial
This repo is tutorial for a Git

Basic commands:

```sh
$ git init         # tworzy nowy podkatalog o nazwie .git, zawierający wszystkie niezbędne pliki — szkielet repozytorium Gita
$ git status
$ git branch       # lista wszystkich i zaznacza obecny branch gwiazdką
$ git add <file>   # dodaje plik
$ git add -A       # dodaje wszystko
$ git commit -m "message"    # tworzy commit z wiadomością
$ git diff         # pokazuje zmiany we wszystkich plikach
$ git log          # podgląd historii
$ git checkout -b <branch_name>    # tworzy gałąź i jednocześnie się na nią przełącza
$ git checkout <branch_name>       # przełącza HEAD na gałąź
$ git checkout HEAD^               # cofa HEAD o jeden(^)
$ git checkout HEAD~5              # cofa HEAD o pięć(~)
$ git push <remote> <branch>       # wysyła zmiany
$ git pull <remote> <branch>       # pobiera zmiany
$ git fetch        # pobiera informacje z repo
$ git stash        # archiwizuje zmiany w schowku
$ git rebase --onto master <branch_name~[numer->parent commitu od którego zaczynam]> <branch_name>
```

Helpful tools:

```sh
$ gitk
```

Online services:

 - [GitHub]
 - [GitLab]