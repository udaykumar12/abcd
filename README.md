echo "# abcd" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:udaykumar12/abcd.git
git push -u origin main
