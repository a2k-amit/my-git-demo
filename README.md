# my-git-demo
Repository For GitHub Learning:<br>
==========================================================================================<br>
Author: Amit Karlekar<br><br>

1. Download Git on system-laptop<br>
2. Check git version: git --version<br>
3. To add username: git config --global user.name "a2k-amit"<br>
4. To add email: git config --global user.email "amit09karlekar@gmail.com"<br>
5. To check what did we add: git config --list<br>
==========================================================================================<br>

1. VS Code Commands:<br>
1. Cloning a repository on our local system(Laptop):<br>
Command: git clone repositoryLink<br>
Command: git clone repositorLink<br>
2. We can go the inside of the fetched folder/directory with a command:<br>
Command: cd insideFolderName<br>
3. To clear the terminal: clear<br>
4. To check the files of the folder: ls (LS)<br>
5. To see hidden files of the folder: ls -Force<br>
6. Checking the status of the code:<br>
Command: git status<br>
==========================================================================================<br>

2. Upload VS Code Changes To Github:<br>
1. Check Status: git status
1.1. Status Type:<br>
untracked - new files that git doesn't yet track<br>
modified - code changed or modified<br>
staged - file is ready to committed<br>
unmodified - unchanged<br><br>

2. Add Command To Track The new Changes That We want To add to the git staging area:<br>
2.1. For single file: git add filename(index.html) - (Note: Check Status - "git status")<br>
2.2 For all files: git add . - (Note: Check Status - "git status")
Check Status: git status<br><br>

3. Commit the changes after add command:<br>
3.1 git commit -m "typeMessage inside double quotes"<br><br>

4. Push the commits to github with Push command:<br>
Command: git push origin main<br>

==========================================================================================<br>

5. init Command to work with changes made on VS Code which is used to create a new git repo from VS Code:<br><br>
5.1 To use the vs code data in github: git init<br>
5.2 Create folder from vs code: cd ..(cd space dot dot to get out of the current folder)<br>
5.3 Make new repository/directory(folder): mkdir giveDirctoryName<br>
5.4 Go to the new directory: cd newDirectoryName<br>
5.5 Make the new directory a git repository: git init<br>
5.6 Check hidden files: ls -Force<br>
5.7 Create two files - html/css<br>
5.8 Check Status: git status<br>
5.9 git add .<br>
5.10 git commit -m "new files added"<br>
5.11 Create new repo on Github<br>
5.12 Add new rep to git: git remote add origin https://github.com/a2k-amit/myLocalRepo.git<br>
5.13 Check version: git remote -v<br.
5.14 To check which branch we are on: git branch<br>
5.15 To change the branch name: git branch -M main<br>
5.16 Test Line Added To check whether it comes on vs code or not.

==========================================================================================<br>

6. Push Github changes to vs code:
6.1 Run: git add file name - git add README.md
6.2 Run: git commit -m "added new information"
6.3 git pull --tags origin main

==========================================================================================<br>

7. Git Branch:
7.1 Check branch name: git branch
7.2  Go to another branch: git checkout branchName
7.3 Create new branch: git checkout -b newBranchName
7.4 Delete a branch: git branch -d featureTwo. Note: we need to move out the branch which we want to delete and open another branch.
7.5 Push vs changes to new branch on Git: Create new branch (7.3) > git add . > git commit -m "describe your changes here" > git push -u origin your-new-branch

7.6 Merge two branch vs code terminal:
- Check branch name: git branch (*secondBranch)
- Pull latest changes from the remote feature branch: git pull origin secondBranch
- Verify you are on the correct branch: git checkout secondBranch
- Merge branches: git merge main or git merge secondBranch
- Uploads the merged changes from your local feature branch to GitHub: git push -u origin secondBranch

7.7 OR from GitHub: click pull request
7.8 To get the changes on laptop: git pull origin main


==========================================================================================<br>

8. In case of merger error/conflicts:
8.1 git merge --abort
8.2 git pull origin branchName --no -edit
8.3 git push origin branchName

==========================================================================================<br>

9. Undoing the changes:
9.1 Case 1 : staged changes

git reset <- file name ->

git reset

9.2 Case 2 : commited changes (for one commit)
git reset HEAD~1

9.3 Case 3 : commited changes (for many commits)

git reset <- commit hash ->

git reset -- hard <- commit hash ->

==========================================================================================<br>

10. Fork: is a new repository that shares code and visibility settings with the original "upstream" repository. It is a rough copy.