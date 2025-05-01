# Project Collaboration Guide  
**For Teammates New to Git**  

Git is a version control tool that tracks commit history and allow users to share their project. By using git, you can write multiple "versions" or branches in the same project. You can also easily back up to previous versions too. 

Conceptually, there are 2 repos. One in your local machine and another one in Github. The one in your local machine is where you make all changes. Then, you need to upload all local changes to the remote repo, to save it on cloud.


## Set Up
Please follow this Youtube video for setting up git: [https://www.youtube.com/watch?v=enYWHZNgXqM](https://www.youtube.com/watch?v=enYWHZNgXqM)

Ask generative AI like ChatGPT or Gemini when you are lost

## Before Editing
synchronize all changes made by other teammate:
``` bash
git pull origin main
```

## After Editing
1. check changes
2. stage all changes
3. add a commit message
4. push up to the remote repo
``` bash
git status
git add .
git commmit -m "Your Commit Message"
git push
```

## Merge Conflict
**Contact each other immediately to solve merge conflict**




