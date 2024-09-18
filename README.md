# git-aide

site pratique : https://www.w3schools.com/git/default.asp

commandes git:


- git init = démarrage de git dans le dossier (il va surveiller et enregistrer toutes les modifications)

- git clone 'lien ssh' = télécharge le projet distant(repository) dans un dossier

- git status = affiche l'état actuel de git (si des fichiers ont été créer, modifié etc...)

- git add 'nom du ou des fichiers' = sélectionne le ou les fichiers qui vont être "commit"

- git commit -m "message du commit" = point de sauvegarde du projet auquel on peut revenir, le message du commit doit résumer les modifications effectuées

- git remote add origin 'lien ssh' = relie le projet distant(repository) au projet local

- git branch 'nom de la branche' = créer une branche, une nouvelle version séparé du projet que l'on peut modifier sans impacter l'autre ou les autres versions du projet

- git checkout 'nom de la branche' = change de branche

- git merge 'nom de la branche à fusionner' = fusionne deux branches

- git branch -d 'nom de la branche à supprimer' = supprime une branche

- git pull origin 'nom de la branche' = télécharge la dernière version du projet

- git push origin 'nom de la branche' = envoie la dernière version du projet





Etapes à suivre lorsque l'on crée un projet (sans branche) :

- créer le dossier

- aller dans le dossier

- $git init

- créer le répertoire sur github et copier le lien ssh

- revenir dans le dossier

- $git remote add origin 'lien ssh'

- ajouter/modifier/supprimer

- $git status

- $git add 'nom du ou des fichiers'

- $git status

- $git commit -m "message du commit"

- $git status

- $git push