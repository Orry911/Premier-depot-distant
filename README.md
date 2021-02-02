# premier-depot-distant

## Github, le drive du dev ?

Un SCM est un source code manager, c'est un outil qui permet à plusieurs développeurs de travailler sur un même projet tout en laissant
une trace de toutes les actions et modifications du code source.


## Configuration de git en local 

Dans le terminal avec la commande git config, on va pouvoir configurer certaines informations afin de signer correctement les commits.

L'username : git config --global user.name "username"

L'adresse mail : git config --global user.email "email"

Pour verifier on peut entrer la commande : git config --global list


## Git Pull

Avec cette commande, on va pouvoir récuperérer le projet distant mis à jour dans notre dépot local

## Git Clone 

Cette commande permet de récupérer une copie d'un dépot distant sur notre machine.
On peut ainsi travailler en local avec VSCode, ce qui est plus pratique que de travailler directement sur github

## Git Add 

Dans VSCOde, on peut ajouter une nouvelle version d'un fichier à la zone de surveillance en cliquant sur le bouton + dans la section
"Controle de code source"

## Git Commit 

Avec cette commande on enregistre dans l'historique une nouvelle version de notre application.Dans VSCode, dans la section "Controle de code source", on
a une zone de saisie pour indiquer le message du commit

## Git Push

Afin de garder aussi ressemblant que possible le dépot local et le depot distant, on va envoyer les modifs sur github avec la commande push
