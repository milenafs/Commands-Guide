<img height="70" src="https://git-scm.com/images/logos/downloads/Git-Logo-White.png"> 

[]

<
----
### 🚩Initialize a remote repository<br>
`git init`
****
### ➕Add changes<br>
All: `git add .`<br>
Specific: `git add file_name.html`
> Add something that wasn't meant to be added?<br>
> `git restore --staged file_name`
****
### 👍Commit<br>
Commit after add: `git commit -m "name of the commit"`<br>
Rename commit after making the commit: `git commit --amend -m "new name of the commit`
> Forget to add somenthing and already made the commit?<br>
> `git add thethingyouforgot` `git commit --amend -m "name of the commit` <br>

> Want to comeback to the past commit?<br>
> `git reset HEAD^ --hard` <br>
****
### 🌿Branch<br>
New branch: `git checkout -b branch_name`<br>
Delete: `git branch -d branch_name`
****
### 🤷Gitgnore<br>
`file_name`
`**folder_name`
`*.extension_name`
***
### 🪠Useful<br>
`git status`
`git log -number_of_commits`
`git log --online`

### Merge<br>
`git merge brach_name`

### Tag
`git tag v1.0`
`git push origin v1.0`
`git checkout v1.0`


## Rebase<br>
`git rebase branch_name`

## Fetch
`git fetch`

## Pull<br>
Pull = Fetch + Rebase<br>
`git fetch`

##

