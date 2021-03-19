Para crea un nuevo repositorio en la línea de comandos

echo "# demostracion" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/bermoz/demostracion.git
git push -u origin master

Para enviar un repositorio existente desde la línea de comandos:

git remote add origin https://github.com/bermoz/demostracion.git
git branch -M master
git push -u origin master