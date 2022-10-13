
# Git

Assuming we have git installed on our machine, we want to run the following commands on command line:

```
 git config --global user.name "Your name here"
 git config --global user.email "your_email@example.com" 
```

This way we tell the world who we are when we make changes to a git repository.

TODO: Autentikaatio?

Let's start by clonin a repository:

- ```git clone <url>```

Now we can enter the repository on our machine:

- ```cd <repo name>```

We can check the current git status. In other words, do we have something that is not added to the Git "tree".

- ```git status```

We usually want to create a new branch when we develop some changes.

- ```git checkout -b <branch name> ```

You can switch between existing branches with:

- ```git checkout main```
- ```git checkout <second_branch>```

If there are changes in the REMOTE of the branch you are working on LOCALLY. You can update your local version with:

- ```git pull``` 

You can check the list of branches you have locally with:

- ```git branch```

When you have changed something locally and want to add it to the REMOTE, you want to do the following:

- ```git pull``` to make sure you know the current state of remote
- ```git status``` to check what changes you have to add
- ```git add <file name>  ``` to define which files are included in the commit
- ```git commit -m "" ``` to finalise and give an explanation for this commit
- ```git push ``` to push your LOCAL changes to the REMOTE
