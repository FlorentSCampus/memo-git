# memo-git

| COMMANDS | DESCRIPTIONS |
|----------|--------------|
|git --version|Afficher la version de git|
|git config --global user.name "Your Name"|Définir un nom utilisateur|
|git config --global user.email "youremail@example.com"|Définir un mail utilisateur|
|git config --global user.username "Username"|Ajouter le nom utilisateur GitHub|
|git config --global user.username|Vérifier que le nom utilisateur GitHub a bien été configuré|
|git init|Initialiser Git dans le dossier|
|git status|Vérifier le statut Git
|git add <file>|Ajouter le fichier (readme.txt) afin qu'il devienne une partie des modifications de Git
|git log|Afficher l'historique des commits|
|git log --oneline|Identique à [git log], mais affiche chaque commit sur une seule ligne|
|git checkout <commit>|Restaurer un fichier|
|git checkout HEAD~<number>|Identique à [git checkout <commit>]|
|git switch -|Rétablir un fichier à son état actuel|
|git checkout main|Identique à [git switch -]|
|git commit -m "message"|Soumettre un message des modifications à l'historique du dépôt Git|
|git diff|Afficher la différence des modifications du fichier|
|git clone <https://url.com>|Cloner le dépôt sur le desktop|
|git tag -a <tagname> -m "message"|Ajouter un tag au commit|
|git fetch|Récupérer des références de commits / branch / tag... depuis un autre dépôt|
|git merge|Fusionner des références de commits / branch / tag...|
