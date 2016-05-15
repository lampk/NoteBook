Book that keeps my note

git subtree split --prefix book -b gh-pages
### force the push of the gh-pages branch to the remote gh-pages branch at origin
git push -f origin gh-pages:gh-pages
### delete the local gh-pages because you will need it: ref
git branch -D gh-pages