cd Documents | mkdir GitBranchesProject | cd GitBranchesProject | git init
mkdir config | mkdir src
cd config | touch app.config
cd .. | touch settings.json
touch .gitignor => config, settings.json, *.log
cd src | touch index.html | git add . | git commit -m "initial commit"
<title>Git Branches Project</title> <h1>Home</h1> | cd .. | git add . | git commit -m "add index.html"
git branch login | git checkout login | touch login.html | git add . | git commit -m "add login.html"
<h1>Login</h1> | git add . | git commit -m "updated login.html"
git checkout master | git branch signup
git checkout signup | touch signup.html | git add . | git commit -m "add signup.html"
<h1>Sign up</h1> | git add . | git commit -m "update signup.html"
git checkout master | git merge login => Fast-forward merge
git merge signup => Three-way merge
Repositrory name: GitBranchesProject
git remote add origin https://.....
git branch -m master main
git push -u origin main
Add a README link => This is my Git Branches Project.
git pull origin main
