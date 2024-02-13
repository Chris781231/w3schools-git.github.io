# hello-world

Hello World repository for Git tutorial
This is an example repository for the Git tutorial on https://w3schools.com

This repository is built step by step in the tutorial.

### Commands

| Command                                        | Description                                                                                                     |
| ---------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| `git --version`                                | Check Git is properly installed and its version number                                                          |
| `git config --global user.name "{yourName}"`   | Change the user name...                                                                                         |
| `git config --global user.email "{yourEmail}"` | ...and e-mail address to your own. You will probably also want to use this when registering to GitHub later on. |
| `git init`                                     | Initialize Git folder                                                                                           |
| `git status`                                   | Check git repo status                                                                                           |
| `git status --short`                           | Compact status                                                                                                  |
| `git add <file>`                               | Add file to the Staging Environment                                                                             |
| `git add --all` or `git add -A`                | Using --all instead of individual filenames will stage all changes (new, modified, and deleted) files           |
| `git commit -m "{message}"`                    | The commit command performs a commit, and the -m "message" adds a message.                                      |
| `git commit -a -m "{message}"`                 | The -a option will automatically stage every changed, already tracked file.                                     |
| `git log`                                      | View the history of commits for repo                                                                            |
| `git <command> -help`                          | See all the available options for the specific command                                                          |
| `git help --all`                               | See all possible commands (SHIFT + G to jump the end of the list, then q to exit the view)                      |
| `git branch {branchName}`                      | Create a new branch                                                                                             |
| `git branch`                                   | View list of branches                                                                                           |
| `git branch -d {branchName}`                   | Delete branch                                                                                                   |
| `git checkout {branchName}`                    | Change branch (Using the -b option on checkout will create a new branch, and move to it, if it does not exist)  |
| `git merge {branchName}`                       | Merge branch with current branch.                                                                               |
