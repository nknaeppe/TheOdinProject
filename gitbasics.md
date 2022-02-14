1. How do you create a new repository on GitHub?
- Go to GitHub page, click plus, give it a name and confirm.
2. How do you copy a repository onto your local machine from GitHub?
- git clone git@github.com:user/repo
3. hat is the default name of your remote connection?
- origin
4. Explain what origin is in git push origin main.
- origin is the default remote connection
5. Explain what main is in git push origin main.
- main is the branch of the repository, main is the main branch, where other branches will be merged into.
6. Explain the two-stage system that Git uses to save files.
- if you add a file to a git repository, the file will be added to a stagin area
After this the file will be commit, which adds it to the repository, with a message a note for the commit is made.
The message should contain, what was done with the commit.
  - git add
  - git commit

7. How do you check the status of your current repository?
- git status
8. How do you add files to the staging area in git?
- git add filename 
9. How do you commit the files in the staging area and add a descriptive message?
- git commit -m "desecriptive message"
10. How do you push your changes to your repository on GitHub?
- git push
- git push origin main
11. How do you look at the history of your previous commits?
- git log
