…or create a new repository on the command line
echo "# demostracion" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/bermoz/demostracion.git
git push -u origin master