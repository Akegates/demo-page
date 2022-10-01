 # Git workflow

 ## Simplier, using `main` (normally, by default it is called `master`) - only for small team/projects!

 1. When you start your work issue `git pull origin main`
 2. Do your work, modify/add/delete files in the repository
 3. When you ready to commit issue `git pull origin main`
 4. If there is no conflict  
   - list the modified files with `git status`
   - `git add <files>`
   - `git commit -m "informational message"`
 5. Issue `git push origin master`  

 ## Using branches

1. When you start your work issue `git pull origin main`
2. Create a new branch with `git checkout -b <branchname>`  

In a cycle you can do steps 3. to 6. several times:

3. Do your work, modify/add/delete files in the repository
4. When you ready to commit issue `git pull origin <branchname>`
5. If there is no conflict  
  - list the modified files with `git status`
  - `git add <files>`
  - `git commit -m "informational message"`
6. Issue `git push origin <branchname>`  
( After the first push you can create a `PR` = `Pull Request` on the Github page of your project )  
  
7. When you are ready with your work merge your branch into `main`  
  - from the Github page on the Pull Request page
  - on the CLI:
```
git checkout master
git merge --squash <branchname>
git commit
```

`--squash` is optional, but it helps to maintain a more followable commit history
