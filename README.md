# Git_course
learning git

write smth

this peregraph is modified


# basics of Git

- `git add file_name (or . or * for all files)` add files to queue.

- `git commit -m "comment of the mdificaton"` make the files we added ready to push .

- `git push` push the files to the repository.

- `git status` view the status of the files.

- `git diff` to see the modification for the current commit.

- `git log` to see all commmits.

- `git pull` get the latest version of repository.

- `git commit --amend`  to edit a comment of a commit.
    >type `i` to start editing => after editing type `esc` so you can so you can switch to command mode => type `:wq` to save and exit or `:q!` to exit without saving.

- `git branch name-of-branch` create branch.

- `git checkout name-of-branch` for switch to a branch (`name-of-branch`).

- `git merge name-of-branch` merging name-of-branch with current branch.

- `git checkout id-of-commit` se positioner sur l'entete du commit.

- `git checkout HEAD^` se deplacer 1 pas sur le commit precedant.

- `git checkout HEAD~{num}` se deplacer en fonction du **num** pas sur le commit precedant.

- `git reset HEAD~1` annule les changement en deplaçant la referance en arriere dans le temps sur un commit elle est utilisé sur les branches locales

- `git revert HEAD` annuler des changement et partager les annulation 