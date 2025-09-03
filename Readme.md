<!-- In the Child Repo -->
<!-- Initial adding subtree -->

git remote add -f base https://github.com/username/project.git
<br/>
git subtree add --prefix=Placeholder base main --squash

git add Placeholder
git commit -m 'message'
git branch -M main
git push -u origin main

<!-- Pulling changes from subtree repo -->

git subtree pull --prefix=Placeholder base main --squash
