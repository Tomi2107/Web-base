Se escapa el nav y el footer, quedan mal articulados con el @media..

No logro colocan los items de nav y footer donde quisiera.

echo "# empty" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/Tomi2107/empty.git
git push -u origin main

----
Renombrar el origin
git remote rm origin

borrar rama
git branch -d main2

git tag
muestras las tag en stage

borrar las inecesarias
$ git tag -d v1.1 v1.2 v2.0 v2.1