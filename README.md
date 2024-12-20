## Version Control
Version control is a system that tracks changes to files over time. It helps developers collaborate, manage code versions, and revert to previous versions if needed. Examples include Git, SVN, and Mercurial.

## Difference Between Git and GitHub

 Git                                                                
                                                                   
 A version control system.                                           
 Tracks code changes locally. 
 | Command-line based.


 Github
 A platform for hosting Git repositories.
  Provides remote repository and collaboration tools.
  Web interface with additional features.     


  ## GitHub Alternatives
  1. **GitLab**
2. **Bitbucket**
3. **SourceForge**

## Difference Between `git fetch` and `git pull`

git fetch
 Downloads changes from the remote repository without merging them. 
 command line:
 **`git fetch`** 

 git pull
 Fetches and merges changes from the remote repository into the current branch. |
command line: **`git fetch`** 


## Git Rebase
**Definition:** `git rebase` is used to integrate changes from one branch into another by rewriting the commit history.

**Command:**
```bash
git rebase branch-name

**git cherry-pick
**Definition:** `git cherry-pick` is used  to apply specific commits from one branch to another.

command: git cherry-pick <commit-hash>