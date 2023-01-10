# Frequently used CLI commands
### (CLI - command line interface - your terminal)

## Git Commands frequently used:

### how to push your code from AWS Cloud9 to GitHub repo
  1. **cd** (change directory) **projectFolderName-yourGitHubUsername**
     * the git commands MUST be run from the relevent project folder on the CLI (terminal)
     * recall the auto fill feature using the Tab key 
  2. **git status**
  3. **git add -A**   (adds all files that haven't been updated into staging phase)
  4. run **git status** again to check if your files have been updated that contain your code.
  5. **git commit -m "your descriptive message of the work completed to this point"**   (or "Submit for grading" if you are done with the project)
  6. run **git status** again
  7. **git push origin main**
     * type in your GitHub username
     * copy your GitHub personal access code in place of password requested (*note cursor will NOT move when access key is pasted*)
  8. Check your project GitHub repository to confirm your push worked correctly
  9.   Congratulations!  You have pushed your work successfully!!!


### how to copy or clone a starter GitHub repo to your AWS Cloud9 IDE
  1. **git clone https://yourProjectGitHubRepo.com**
     * *ALWAYS run your git clone command from the Root Directory - **/environment $** *


## Commanly used Linux Commands
* **cd newFolderName**  to move the command line to open a directory (folder)
* **cd ..**  to move up a folder or directory - as in from project folder to root directory
* **ls -al**  list all files in a long listing (detailed) format
* **ls**  list all files in a directory
* **touch newFileName** Create an empty file within the current directory
* **mkdir newDirectory**  Create a directory (folder)
