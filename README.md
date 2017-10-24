# GitHub Tutorial

_by Oula Mahfouz_

---
## Git vs. GitHub
**Git:**
* git takes a snapshot of your code(git is used to save your code and any changes that you have done )
 
**GutHub:**
* github is where the code goes and stores its self in a cloud(Github is a hosting website where you can store your git commits)

---
## Initial Setup

**Making a github account:**

You have to put in you email and make a password. Self explanitory and its your choice to what you choose to put.

---
To set up your SSH key:
#### _This is something you only do once!_

**In Git:**
* Go into your github account
* Head to settings (the top right arrow with your profile)
* To the left press "SSH and GPG keys"
* Press new SSH key
* Tittle it: _Cloud 9_

**In Cloud 9:**
* Login to cloud 9
* In the cloud 9 tap the gear icon
* To the left press SSH Keys
* Copy the **2nd** big peice of code

**Back into Guthub**
* Paste in your git hub "key" place
* then go ahead and press "add SSH key"



---
## Repository Setup
**Cloud9**

In your cloud9 work space you have to create a directory and a "first-repo":

**make a new folder**(i think title should be how to commit)
* to init you type `git init`
* to add you type `git add .`
* to commit you type `git commit -m "put your message here" `

**making your first repo** (do these steps)(this should go before ^)
* make sure your on your workspace
* mkdir `repo name`
* cd first-repo
* git init

**makiing a README.md file**
* touch README.md
* _open it_ type `this is my "repo name"`
* `git add .`
* `git commit -m "message here"`
* `git push`



---
## Workflow & Commands
**These commands are some of what you will need to know and use almost everytime that you are on cloud9**
```
1. git add . 
2. git status
3. git commit -m "message here"
4. git push
```

1. `git status` to see which files are staged to be committed.
2. `git add ` to add a file to the stage `git add .` is to add all your files to the stage
3. `git commit -m "message here"`  takes a snapshot of the files on the stage. you use a quote and that quote is a message for your current commit which is there now
4. `git push`  sends commits from you local repository to your remote repository

---
## Rolling Back Changes

**To Undo Edit, Add, Commit, and Push**
* Edit: type git status and read it it tell you to use git checkout -- <file>.... this command undo's the edit you made to the file.
* Add:  type git status it should be green. If you type git status again, it should tell you how to un-add a file. Read what it says to un-add you type git reset HEAD <file>...
* Commit: to undo the commit you use git reset --soft HEAD^
* Push: type git log which shows you a log of your previous commits. there you see the SHA key of your commit next you revert which undo's your push.

















