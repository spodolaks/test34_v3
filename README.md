…or create a new repository on the command line
echo "# test34_v3" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/spodolaks/test34_v3.git
git push -u origin main