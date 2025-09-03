<!-- In the Child Repo -->
<!-- Initial adding subtree -->
<h1>In the Child Repo</h1>
<h3>Initial adding subtree</h3>
<pre>
  git remote add -f base https://github.com/username/project.git
  git subtree add --prefix=Placeholder base main --squash
  git add Placeholder
  git commit -m 'message'
  git branch -M main
  git push -u origin main
</pre>

<!-- Pulling changes from subtree repo -->
<h3>Pulling changes from subtree repo</h3>
<pre>
  git subtree pull --prefix=Placeholder base main --squash
</pre>
