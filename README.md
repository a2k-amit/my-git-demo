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

- VS Code Commands:<br>
1. Cloning a repository on our local system(Laptop):<br>
Command: git clone repositorLink<br>
2. We can go the inside of the fetched folder/directory with a command:<br>
Command: cd insideFolderName<br>
3. To clear the terminal: clear<br>
4. To check the files of the folder: ls (LS)<br>
5. To see hidden files of the folder: ls -Folder<br>
6. Checking the status of the code:<br>
Command: git status<br>
==========================================================================================<br>

- Upload VS Code Changes To Github:<br>
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
