# Projet tutoré

Dépôt du code du projet "Random Forest"


#Rappel git 

Avant de commencer à coder :
- git branch (pour voir sur quelle branche vous êtes ) et si vous n'êtes pas sur la master :git checkout master
- git pull ​ (on met à jour la master avec les modifications des autres)
- git checkout {sa branche develop} ​ (on retourne sur sa branche)
- git merge master (pour mettre à jour sa branche)
A partir de ce moment là on est sur sa branche qui est à jour avec toutes les
modifs les plus récentes. On peut coder et faire des commits sur sa branche en
local.

Pour faire un commit :git add .
puis  git commit -m "nomDeCommit"


Une fois qu’on a fini de coder :
- git checkout master ​ (aller sur la master)
- git pull ​ (on met à jour la master au cas où qqun a merge des modifs sur la
develop pendant qu’on codait)
- git merge {sa branche} ​ (pour ajouter ses modifs au projet)
- git push  (on push la develop pour que les autres puissent récupérer
les modifications)

L’idée est que : Dès qu’un truc est fait, il part sur la master et les autres
peuvent le récupérer. De même, on récupère sur sa branche les modifs des
autres enregistrées sur la develop dès que possible.

