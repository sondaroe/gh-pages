# gh-pages
echo "# gh-pages" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/sondaroe/gh-pages.git
git push -u origin master
