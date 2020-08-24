# Something about Git

If You want to contribute on other repositories then do these steps :
===============================================

## 1. Fork this repository
## 2. Clone in your system
## 3. Do push on your repository

# Steps to push on your repository :

#### Chekout to branch if you wanted to push on branch
### git checkout -b branch_name
## 1. git add .
## 2. git commit -m 'Commit message'
## 3. git push origin master/branch_name
## 4. Sent pull request to original repository
## 5. Wait to merge on original repository

How to get changes of original repository to your forked repository :
=======================================================================
 
## 1. Add the remote, call it "upstream":

### git remote add upstream https://github.com/whoever/whatever.git

## 2. Fetch all the branches of that remote into remote-tracking branches, such as upstream/master:

### git fetch upstream

## 3. Make sure that you're on your master branch:

### git checkout master

## 4. Rewrite your master branch so that any commits of yours that aren't already in upstream/master are replayed on top of that other branch:

### git rebase upstream/master

How to remove conflicts from your branch
=======================================================================

## 1. Checkout to the branch from which you created the PR

## 2. Run git pull upstream master

## 3. Go to the files that shows CONFLICT in the terminal or have c tag (In VSCODE) along with the file in the left panel.

## 4. Go to the highlited lines of that file and click accept both changes.

## 5. Then edit your code to make sure the functionality is working fine and commit the changes and push it to your branch using git push original <Your_branch_name>
