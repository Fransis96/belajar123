# BELAJAR GITHUB

## …or create a new repository on the command line
echo "# tes" >> README.md \n
git init \n
git add README.md \n
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/fr/tester.git
git push -u origin main

## …or push an existing repository from the command line
git remote add origin https://github.com/fr/tester.git
git branch -M main
git push -u origin main