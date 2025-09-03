<!-- In the Child Repo -->
<!-- Initial adding subtree -->
<h1>In the Child Repo</h1>
<h3>Initial adding subtree</h3>
git remote add -f base https://github.com/username/project.git
<br/>
git subtree add --prefix=Placeholder base main --squash
<br/>
git add Placeholder
<br/>
git commit -m 'message'
<br/>
git branch -M main
<br/>
git push -u origin main
<br/>

<!-- Pulling changes from subtree repo -->
<h3>Pulling changes from subtree repo</h3>
git subtree pull --prefix=Placeholder base main --squash
