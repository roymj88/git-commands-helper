# git-commands-helper : Basic git commands

Here is a list of some basic Git commands that will help you get started with git.

1. **Checkout a new branch**
   ```
   git clone git-repo-url
   eg:-   
   git clone https://github.com/roymj88/git-helper.git
      
   ```
2. **Create a new local repository**
   ```
   git init
   ```
   
3. **Create a new branch from current working branch and switch to it**

   ```
   git checkout -b <new-branch-name>
   ```
   
4. **Switch to a new branch**

   ```
   git branch <branch-name>
   ```
   
5. **List all available branches**
   ```
   git branch
   ```
   
6. **Check status of files**
   ```
   git status
   ```
7. **Add files for commit**
   ```
   git add <file-name>
   OR
   git add <file-name-1> <file-name-2> <file-name3>
   OR
   git add *
   
   ```
7. **Remove files for commit**
   ```
   git rm <file-name>
   ```
   
8. **Commit**
   ```
   git commit -m "Message for commit"
   ```

9. **Pull - Update local repo with latest update from server**
   ```
   git pull 
   ```

10. **Push - Update changes to repository**
   ```
   git push origin master 
   #Updates 'master' branch
   
   git push origin <branch-name> 
   #Updates corresponding branch
   ```
   
11. **Stash - Store changes without commiting**
   ```
   git stash
   ```
   
12. **Stash Apply - Apply stashed changes**
   ```
   git stash apply
   ```
   
13. **Merge**
   ```
   git merge <branch-name>
   #Merges a different branch into your active branch
   ```

14. **Setting username in Git**
   ```
   git config --global user.name "user name"
   #Set a new user name
   
   git config --global user.name
   #Displays the user name
   ```
   
15. **Setting email in Git**
   ```
   git config --global user.email "your_email@example.com"
   ```
   
16. **Modify the Previous Commit's Message**

   ```
   git commit --amend -m "New commit message"
   ```
   
17. **View commits of a certain author** 
    ```
    git log --author=user.name
    ```
   
18. **View all commits** 
    ```
    git log
    ```

19. **List of tags**
   ```
   git tag
   ```
   
20. **Config value for color**
   ```
   #Edit Color scheme
   
   color.status=auto
   color.interactive=auto
   color.diff=auto
   ```
21. **Export Git Repo**

   ```
   git archive --format=zip -9 HEAD -o <file-name>
   ```
22. **Search**

   ```
   #Search the working directory for foo()
   git grep "foo()"
   ```
   
