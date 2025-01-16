### create a new repository on the command line

echo "# Python" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/RishavMishraRM/Python.git
git push -u origin main

### push an existing repository from the command line

git remote add origin https://github.com/RishavMishraRM/Python.git
git branch -M main
git push -u origin main

### Check the remote to git

-- git remote -v

### Remove the remote from Git

-- git remote rm origin
