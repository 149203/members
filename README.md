**Readme**

This is the Las Vegas FCC Members Page. If you'd like to introduce yourself to the group, or add any of your links (profile page, social media links) this is the place to do it. It will also give you a chance to learn the basic Git workflow.

First, clone this repository.

Create a branch (on the command line this would be `git checkout -b {myNewBranch}` (Name it anything you want, don't include the curly brackets) 

Then create a new folder, name the folder however you want but it would be best if it was your name, your FCC username / Github username, etc. Then create one or more text files to tell the group who you are, what you're working on or whatever you want. 

When you are finished, you'll want to:

1. `git checkout master`

2. `git pull` to pull in any changes that have been made since you cloned the repo.

3. go back to your branch - `git checkout {mybranch}`

4. `git merge master` (if step 3 said 'Already up to date' then this is unnecessary, but won't hurt anything)

5. Now you'll need to add your files to Git - You'll need to do a `git add` and a `git commit`, you can do this in different ways, but here is my way... 
5A. `git add -A` (add All files) 
5B. `git status` (make sure I didn't do anything stupid)
5C. `git commit -m 'Ben Denzer initial commit'`

6. `git push origin {mybranch}` (FYI 'origin' is the name of the remote repository where you cloned from - this name can be changed, and you can have multiple remote repos, but on basic stuff like this, origin is always where you cloned from)
