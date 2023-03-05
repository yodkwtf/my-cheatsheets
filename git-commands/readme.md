# Git Commands Cheatsheet

This cheatsheet includes all the basic git commands. I keep updating the cheatsheet as and when I learn any new command.

## Commands

| Command                          |                                   Purpose                                    |
| :------------------------------- | :--------------------------------------------------------------------------: |
| `cd <directory>`                 |                          Switch between directories                          |
| `ls`                             |           will **l**i**s**t the contents of the current directory            |
| `pwd`                            |      **P**rint **W**orking **D**irectory - prints the current directory      |
| `git init`                       |                               Intialize a repo                               |
| `git status`                     |                      Check the tracked status of files                       |
| `git add <file>`                 |                        Track changes to a file to git                        |
| `git add .`                      |                    Track changes to all the files to git                     |
| `git commit -m <'msg'>`          |                         Save tracked changes to git                          |
| `git push`                       |  Upload tracked changes to a remote repo online (on something like github)   |
| `git log`                        |                 See a list of all the commits made to a repo                 |
| `git clone <REPO_URL>`           |      Download a repo as it is from internet (from somwhere like github)      |
| `git pull`                       |             Pull changes from a remote repo to your local system             |
| `git reset`                      |                            Undo a recent git add                             |
| `git reset HEAD~1`               |                         Undo the most recent commit                          |
| `git reset <commit hash code>`   |                      Undo commits upto specified commit                      |
| `rmdir -Force -Recurse .git`     |               Remove the `.git` folder from project [WINDOWS]                |
| `rm -rf .git`                    |                 Remove the `.git` folder from project [MAC]                  |
| `git checkout -b <branch-name>`  |                Create and switch to the new specified branch                 |
| `git checkout <branch-name>`     |                        Switch to the specified branch                        |
| `git push origin <branch-name>`  |                          Push to a specified branch                          |
| `git remote -v`                  |                 Check the origin of a git project (repo url)                 |
| `git reset --hard <commit_code>` | Undo's commits and pushes till specified commit (deletes files, make backup) |
| `git push -f`                    |              Force push current code (must after prev command)               |

## Conclusion

Thank you for visiting this cheatsheet!

If you found it helpful please check out more of my work on [yodkwtf.com](https://yodkwtf.com) or follow me on [twitter](https://twitter.com/yodkwtf).
I also run a small youtube channel called [Yodkwtf Academy](https://youtube.com/yodkwtf).
