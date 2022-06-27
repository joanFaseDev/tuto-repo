# Tutorial Git & GitHub

## Intro

**Git** est un logiciel de gestion de version permettant de stocker une collection de fichiers en gardant en mémoire la chronologie ainsi que la nature des changements effectués dessus.

## Commandes Git

_git clone_ -> permet de cloner un dépôt hébergé ailleurs (e.g. Github) dans un répertoire sur sa machine locale.

_git add_ -> met à jour le contenu de l'index afin de préparer la prochaine sauvegarde.

_git commit_ -> enregistre les modifications dans le dépôt.

_git push_ -> mets à jour le dépôt distant (e.g. Github) par rapport au dépôt local.
_git push origin main_ -> _origin_ est un alias utilisé pour désigner l'URL du dépôt distant. _main_ fait référence à la branche du dépôt.

_git remote -v_ -> affiche les URLs des dépôts.

_git pull_ -> mets à jour le dépôt local par rapport au dépôt distant en téléchargeant les changements ayant eu lieu sur ce dernier (_git pull_ est l'inverse de _git push_).

_git status_ -> affiche tous les fichiers du dépôt en cours ayant été crées, effacés ou modifiés.

## Commandes Git Bash

_git --version_ -> affiche la version de Git utilisée actuellement.

_pwd_ (**print working directory**) -> affiche le répertoire dans lequel on se trouve actuellement.

_cd_ (**change directory**) + répertoire -> permet de changer de répertoire.

_ls_ (**list directory contents**) -> affiche le contenu du répertoire.

_ls -la_ (**list all**) -> affiche tous le contenu du répertoire même les fichiers cachés.

## Ressources externes

https://explainshell.com/explain?cmd=cd
