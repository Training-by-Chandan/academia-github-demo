Actions Performed:
- Created repo
- Created files for the repo
- git add .
- git commit -m "Initial Commit"
- Add files to gitignore
- git add . ; git commit -m "Added git ignore"
- Add origin using command:
    git remote add origin git@github.com/Training-by-Chandan/academia-github-demo.git
-Push it:
    git push origin main
-Created a change in origin repo online
-Tried to push 
    unpulled changes error
-Hit the command:
    git pull origin main
-Conflict occurs 
- Resolve the conflict
- Hit the command:
    git commit -am "Conflict resolved"
    git push origin main
- Created branches
    git branch _chandan
    git chekout _chandan
- Added files on those branches
- Commited those branches
- Switched to main branch
    git chekout main


- Trying to merge:
    To get info of all branch
     git fetch
    To check sagar's update 
     git checkout sagar
     git pull origin sagar
- To merge sagar's code
- Going back to chandan sir's branch
    - git checkout _chandan
- Make sure local branch and remote branch is updated.
- Check sagar's brach
     git checkout sagar
     git pull origin sagar
-If it is updated goto chandan branch
     git checkout _chandan
-Merge it:
     git merge sagar 
- To check logs
    git log --online
- Finally push locally merged to origin
    git push origin _chandan

-GUI setup to protect branches
-GUI demonstration of pull requests and its review.