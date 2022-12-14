# Workaround Git/GitHub

A place where I can brush my git/github skills.
**`Note: this repo is used for documenting my experiments with version control..`**

### what I learned
1. > ***git clone url dirname.***
clones the remote repo into dirname.
2. how to keep features branch up to date.  
    > git checkout dev
  git pull
  git checkout feature/$1
  git merge dev
  git push

3. **how to rename the branch remotely as well as locally**

   > to rename branch locally use  
   git branch -m oldname newname  

   >to rename branch remotely
    git branch -m oldname newname
    git push origin --delete oldname
    git push origin -u newname