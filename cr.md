# Compte-rendu - Conduite de projet - L2

### Noms et Pseudo GitHub

TROTTIER Arthur (WarNN) & SEBILLE Florian (kirozz)

### Dépôts distants

https://github.com/kirozz/tp-note-local.git

https://github.com/kirozz/tp-note-distant.git

https://github.com/kirozz/conduite-projet.git


## 1) Création dépôt local

`git init`

`touch README.md`

`touch .gitignore`

`git add -A`

`git commit -m "version 1"`

`git remote add origin https://github.com/kirozz/tp-note-local.git`

`git push --set-upstream origin master`

## 2) Récupération dépôt distant

`git clone git@github.com:kirozz/tp-note-distant.git`

`touch README.md`

```
git add -A
git commit -m "README"
git push
```

## 3) Pull Request

`git clone git@github.com:kirozz/conduite-projet.git`

```
git add -A
git commit -m "ajout nom README"
git push
```
## 4) Merge
a- Un merge doit être fait lorsque 2 versions d'un même fichier rentrent en conflit. C'est à dire quand 2 collaborateurs poussent un même fichier avec un contenu différent pour certaines lignes.

b- Dans le cas d'un merge, il faut modifier le fichier obtenu et régler les conflits aux lignes nécessaires.
