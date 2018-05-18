# hello-world
Guide pour débuter : https://guides.github.com/activities/hello-world/

#Commande Linux
Cloner : git clone https://github.com/AlexisLiebherr/hello-world
Branching : 
- git checkout -b test  (créer une branche test)
- git status (pour voir ce qu'il se passe)
- git branch (lister les branches, celle avec l'astérisque indique sur laquelle on se trouve)
- git checkout nom.fichier (supprimer les modifications sur le fichier)
- git checkout master (revenir sur la branche master)
- git branch -D test (supprimer la branche test)
- git add nom.fichier (ajouter les modifications du fichier)
- git commit nom.fichier (ajouter le fichier modifié à la liste des fichiers à pousser dans la branche)
- git log --branches --not --remotes (lister les commits non poussés dans la branche)
- git push origin test (pousser les commits dans la branche, puis merger depuis le site de Github)
- git pull origin master (mettre à jour master sur le PC local suite au merge sur le site de Github)
