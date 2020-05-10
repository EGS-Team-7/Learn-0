





# The Answer

Stuck? This document is here to help.  
Each section below answers 'how do I' for every step.  
(Try not to peak ahead!)  
The whole point of this exercise is to help _you_!  




## Step 1

```bash
$ git clone https://github.com/EGS-Team-7/Learn-0
Cloning into 'Learn-0'...
remote: Enumerating objects: 14, done.
remote: Counting objects: 100% (14/14), done.
remote: Compressing objects: 100% (10/10), done.
remote: Total 14 (delta 1), reused 9 (delta 0), pack-reused 0
Unpacking objects: 100% (14/14), done.
```




## Step 2

```bash
$ cd Learn-0

$ git branch -a
* master
  dev
  remotes/origin/HEAD -> origin/master
  remotes/origin/master

$ git checkout dev
Switched to branch 'dev'
Your branch is up to date with 'dev'.
```




## Step 3

```bash
$ git checkout -b peter-mangelsdorf
Switched to a new branch 'peter-mangelsdorf'
```




## Step 5

```markdown
## Signatures

 - Billy Bob Jenkins
 - Peter Mangelsdorf

```




## Step 6

```bash
$ git status
On branch dev
Your branch is up to date with 'dev'.

Changes not staged for commit:
  (use "git add <file>..." to update what will be committed)
  (use "git checkout -- <file>..." to discard changes in working directory)

        modified:   README.md

no changes added to commit (use "git add" and/or "git commit -a")

$ git add README.md

$ git commit -m "Adding Peter's Signature"
[dev ec882c9] Adding Peter's Signature
 1 file changed, 1 insertion(+), 1 deletion(-)
```




## Step 7

```bash
$ git push --set-origin peter-mangelsdorf
```




## Step 8

```bash
$ git checkout dev
Switched to branch 'dev'
Your branch is ahead of 'dev'.

$ git pull
Already up to date.

$ git checkout peter-mangelsdorf
Switched to branch 'peter-mangelsdorf'
Your branch is up to date with 'peter-mangelsdorf'.

$ git merge dev

$ git add .

$ git commit -m"Finalizing Changes to Readme"

$ git push
```




## Step 9

 - Open an Internet browser and navigate to the repo
 - At the top of the page, click "Pull requests"
 - The "Pulls" page should open. Now click "New pull request"
 - Select `base: master` on the left and `compare: your-branch` on the right
 - Click "Create pull request"




## Step 11

 - Open an Internet browser and navigate to the repo
 - At the top of the page, click "Pull requests"
 - Click on the pull request your friend made
 - The request page should open. Click "Review"
 - The review page should open. Click "Approve Changes"





