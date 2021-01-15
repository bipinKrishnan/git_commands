Complete guide is [here](https://www.dataschool.io/how-to-contribute-on-github/)

### Commit to main branch
    1. git add .
    2. git commit -m <commit_message>
    3. git push

### Make a new branch
    1. clone the repo
    2. change directory to the cloned repo
    3. git branch <branch_name>

### Switching branches
    1. git checkout <branch_name>

### Check the branch name you are currently working on
    1. git branch

### Push changes to a branch other than main branch
    1. git add .
    2. git commit -m <commit_message>
    3. git push origin <branch_name>
    
### Remove a branch remotely
    1. git push origin --delete <branch_name>
    
### Contribute to opensource
    1. Fork the repo
    2. git clone <url_forked_repo>
    3. git remote add origin <url_forked_repo>
    (This sets the origin as forked repo)
    
    4. git remote add upstream <url_original_repo>
    (This sets the upstream repo as the original repo)
    
    5. git pull upstream master
    (pulls all the changes from master branch of upstream repo)
    
    6. git branch <your_branch>
    7. git checkout <your_branch>
    8. Make the required changes then add and commit
    9. git push origin <your_branch>
    10. Do a pull request/merge request
