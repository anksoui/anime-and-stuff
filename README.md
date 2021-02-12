# anime-and-stuff
git fetch origin
git checkout -b imgbot origin/imgbot
git merge main
git checkout main
git merge --no-ff imgbot
git push origin main
