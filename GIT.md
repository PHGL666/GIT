1. Jamais travailler sur le document d'un collegue
2. Toujours push de cette manière
git pullg
git add .
git commit -am "message"
pit push
3. on écrit toujours un VRAI message de commit


# Gitbash : 

## Git Clone
git clone SSHREPO
> sur github sélectionner branche dev
git checkout -b dev
> pour afficher la commande
git pull
> selectionner commande et copier, mettre à jour la ligne avec dev
git branch --set-upstream-to=origin/dev dev
> pour télécharger
git pull



supprimer la branch dev
> mise au rebut
git stash 
> on va sur la branche main
git checkout main
> supprimer la branche dev (delete)
git branch -d dev
> récupérer la branche dev directement du repo
git pull origin dev

pour récupérer le travail d'un collègue
git pull


pour voir tous les fichier et l'arborescence global (où se trouve .git par exemple)
ls -la


supprimer un repository, doit utiliser recursif et force
rm -rf DOSSIER
remove recursifforce


git log
copié le numéro du commit
sortir du log
git checkout numéroducommit 


git stash
git reset --hard numéroducommit


OBS 
> exemple pour forcer un push sur branche dev2
git push origin -dev2 --force


> dans dossier dolibar
git rm -r --cached settings
cd ..
git pull --force
git commit -am "fusion ph"


git add -i


git log

git revert IDduCommit
git reset --hard id
git push --force

git branch
git branch nom
git checkout nom
git checkout -b nom

# LES MERGES
git checkout main
git merge branche_à_rappatrier

# SUPPRIMER BRANCHE
git branch -d nom_branche


# PULL une branche
git pull origin nomdelabranche

