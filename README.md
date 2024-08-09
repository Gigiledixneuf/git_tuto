# Documentation du tuto git

## Initialisation du depot

***bash
git init
git remote add origin SSH_REPOT 
***

## Envoyer un commit sur le repos distant
***bash
git add
git commit -m "Ajout d'un commit"
git push origine main or master
*** 

## Creation d'une branche
***bash
git checkout -b NOM_BRANCHE
git checkout NOM_BRANCH
***

## Pour merger une branche
***bash
git checkout main
git merge develop 
***
Pour les bonnes pratiques, on va integrerla notion de revue de code. Pour cela, on va créer une branche, faire des modifications, les envoyer sur le dépot distant, puis créer une pull request pour demander un revu de code. Let's goooo.

## RAJOUT
On a rajouté des fichier html et css pour s'exercer, on a travailler sur les buttons pour la lecon 3

