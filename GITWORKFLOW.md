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
