git init
git add .
git commit -m "first commit"
git checkout -b gh-pages
git branch -d master
git remote add origin git@github.com:davidascher/component-test.git
git push -u origin gh-pages