g�t init
g�t add README.txt
g�t commit -m "Premi�re version"
git remote add origin https://github.com/Hugo0801/partielles.git
git push -u origin master


git branch ajout-code.txt
git checkout ajout-code.txt
git add .\code.txt
git commit -m "1er version de code.txt"
git commit -m "2e version"
g�t merge master
git push -u origin ajout-code.txt

g�t checkout master
git commit .\README.txt -m "3e version"
git push -u origin master