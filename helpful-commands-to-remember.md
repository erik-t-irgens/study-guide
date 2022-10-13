## Commands to Remember! 
Here's a list of categories and commands related to them that you may want to remember. I've tried to include everything that is within the first course section at Epicodus, but please keep building this and making it your own! :) 

### The Terminal
Here's a list of helpful commands that we may use frequently during this course section.

>```ls -a```: View the current directory's contents. The `-a` tag will make it so you will also see the "hidden" files (Which start with .)

>```cd ..```: Move out of the current directory to the directory above (up one)

>`cd nameOfDirectory`: Move into the directory that you list (replace `nameOfDirectory` with the name of the directory in this command)

>`mkdir name`: Create a folder/directory in the current directory, with the name you place (replace `name` with your desired folder name in this commands)

>`touch filename`: Create a file with the name you desire. Make sure to also add a file extension (such as .txt, .md, .js, whatever filetype you wish the file to be)

>`rm FILENAME`: Delete the designated file name.

>`rm -i DIRECTORYNAME`: Delete every file within a directory, one by one, with a prompt coming up to confirm deletion (Pressing Y for yes or N for no)

>`rm -rf DIRECTORYNAME`: Remove files recursively, in a forced manner, from the specified DIRECTORY. **THIS IS NOT RECOMMENDED**

### VSCode in the Terminal

>`code .`: Open the current directory in a VSCode editor, with all the files and subdirectories it contains. 


### Git Commands

>`git status`: Check the current status of the tracked git project directory. This will list changes and untracked changes in the current project. If you are hoping to **not find** a git repo at your current location (such as the Desktop), you will see `fatal: not a git repository` as the response that you want.

>`git init`: Initalize a git repository in the current directory.

>`git remote REF LINK`: Add a reference to a remote repository. 

>`git add .`: Add changes to track (all files in the directory)

>`git commit -m "message"`: Create a commit with a message describing the commit/changes 

>`git push LOCATION BRANCH`: Pushes the current commits/changes to a remote LOCATION from the current BRANCH



### Project Workflow

1. First, create a folder that you are going to build your project within. 
    >`mkdir nameOfProject` 
    
    >Replace nameOfProject with your desired project/directory name

2. Navigate into this project folder. 
    >`cd nameOfProject`
    
    >Same as above. Replace nameOfProject

3. Initalize this project directory as a git repository. 
    >`git init`

4. Navigate to GitHub.com on your browser. Create a new repository of the desired project name. 
5. Copy a link to this project that you've just created.
6. Back in the terminal, add a *remote reference* to this link.
    >`git remote add YOURINITIALS LINKTOREPOSITORY` 
    
    >Replace YOURINITIALS with your initials, and replace LINKTOREPOSITORY with the link you copied
7. Start adding your necessary project files and making changes to this repository. Here's an example: 
    >`touch exmaple.html`

    >`touch README.md`

8. As you work, make sure to create frequent commits to track your changes and progress. First, add the changes you wish to track.
    >`git add .` 
    
    >This will add all files within the current directory. This is fine, but you may also replace `.` with the name of the file

9. Create a commit for the changes you've just tracked, and create a message that describes the change. The message should finish the sentence "It will..." There is an example below. 
    >`git commit -m "Add example.html and README.md"`

10. Push the changes to your online repository that you've added a reference to.
    >`git push YOURINITIALS BRANCHNAME` 
    
    >Replace YOURINITIALS with your initials, and replace BRANCHNAME with the current branch, most likely `main` or `master`

11. Repeat steps 8 through 10 as you continue to make additions and changes to your project files. 




