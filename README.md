# MyHouse
Application de recherche de logement a Dakar
# Comment installer?
Pour installer , il faut faire un clone du projet

git clone https://github.com/hamirkd/MyHouse.git

ouvrir android studio et importer le projet via l'IDE

# Gestion des branches
# Pour afficher la liste des branches

git branch

# Pour créer une branche (NouvelleBranche) à partir de master

git checkout master
git branch NouvelleBranche
git checkout NouvelleBranche

# Pour faire une mise à jour sur la branche distante nouvellement créée
git add .
ou
git add -A
git commit -m "Un message spéficifique liée au modification éffectuée sur le projet"
git push origin NouvelleBranche

# Pour supprimer une branche
git branch -D NouvelleBranche

# Pour faire la mise à jour de la branche locale (master)
git pull origin master
ou
git fetch origin master
