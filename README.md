# aspirantes-mir-ejercicio-3

Solucion ejercicio 3

mkdir ejercicio03

cd ejercicio03

fsutil file createnew index.html 0

code .
fsutil file createnew .env 0

fsutil file createnew .gitignore 0

git init

git add .

git commit -m "Cambios en la rama develop"

git status


git checkout master

git merge develop

git diff

git log
commit ac6d5dce662668742cc0d5bd26c8afa92a6839ec (HEAD -> master)
Author: esteisy02 <esteisygiraldo16@gmail.com>
Date:   Sun Mar 5 22:57:25 2023 -0500

    Cambios en la rama develop

git diff ac6d5dce662668742cc0d5bd26c8afa92a6839ec

git ls-files --other --ignored --exclude-standard

git status
On branch master
nothing to commit, working tree clean

git branch -M main
git remote add origin https://github.com/esteisy02/aspirantes-mir-ejercicio-3.git
git push -u origin main

