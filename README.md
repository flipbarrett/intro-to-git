• .git directory (repository)
Checkout the project to the working directory.
Where all the spanshots are stored.

• Working directory
Are where all the files and directories and changes are living all the time.

• Staging area
Files and directories that we explicitly add to the staging area
(Where files live when they are added but not commited to the repository.)

Commands:
• git status -> tells you what has been included in the tracking process of git (also gives hints ).
• git add -> adds a file to the tracking process.
 - git add *.typeoffile(eg: html) can add all files of that type.
 - git add -A -> adds all files and folders (hidden and visible).
• git commit -m"Message here"-> Save your changes to the local repository.
• git log -> shows a brief history of all commits.
• git reset HEAD <file> -> removes a file from the staging area. 

Method: 
•git ignore: 
       - create hidden file .gitignore.
       - include the names of the files you want to ignore within above file.
       - git add .gitignore file.
       - git commit -m"Hide files".


note: adding a . before the name creates a hidden file.