Voici les commandes de bases pour git

#gestion du dépôt

git clone <url:ssh|https>  => cloner un dépôt distant en local (copie)

git fetch => récupère un maximum d'infos du dépôts (branches)

#branches

git branch => lister les branches
git checkout <branche> => se déplacer sur une branche existante
git checkout -b <branche> => crée et se déplace sur une nouvelle branche

git status => donne l'état de la branche actuelle

git pull => vient récupérer les changements depuis le remote sur le local

#commits
#après une/des modification(s) vous pouvez ajouter ces/cette modification(s) et la documenter (message), pour ensuite la/les mettre en ligne.

git add <fichier> => ajouter le fichier nouvellement crée ou modifié au prochain commit
git commit -m "message" => créer le commit avec les ajouts précédents accompagné d'un message
git push => pousser le commit en ligne

git push --set-upstream origin <remote-branch> => pour une branche nouvellement créée, il faut la connecter au remote
