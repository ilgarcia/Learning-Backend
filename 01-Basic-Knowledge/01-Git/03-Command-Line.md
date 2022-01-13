# The Command Line
there is a lot of ways to use Git, there are the original command-line tools, and there ara many graphical user interfaces (GUIs) of varying capabilities.



**Getting Help**
```
git help <verb>
```
```
git <verb> <Options>
```
**Options:**

`--help`  > Getting help

`-h`  > Getting help

## GIT Basics

### Getting a git repository

**1. Take a local directory and turn it into a git repository**
```
git init
```
**2. Clone an existing Git repository from elsewhere**
```
git clone <url> (<directory name>)
```
**Checking the status of your files**
```
git status <Options>
```
**Options:**

`-s`  > Simplified status

**Tracking/Staging files** 
```
git add <Options> 
```
**Options:**

`<file>`  > Add file to staged area

`*` > Add all files to staged area

`-A` > Add all files to staged area

`--all` > Add all files to staged area

**Ignoring files**
create a file named `.gitignore` 

<p>
  <a href="https://github.com/github/gitignore">File examples for dozens of projects and languages</a>
</p>

**Unstaged/Staged changes**
```
git diff
```

**Staged/Committed changes**
```
git diff <Options> 
```
**Options**

`--staged`  > Staged/Committed changes

`--cached`  > Staged/Committed changes

**git diff in an External Tool**
```
git difftool
```
:rotating_light: Include a nice description of changes when you submit your pull request (PR)

**Committing your changes**
```
git commit <Options>
```
**Options:**

`-v`  > Also puts the diff of your change in the editor

`-m "text"`  > Commit message inline

`-a`  > Skip the staging area

**Removing files from tracked files**
```
git rm <Options>
```
**Options:**

`<file>`  > remove file from tracked

`--cached <file>`  > remove file from staged

`<pattern>`  > remove files with this pattern

**Moving files**
```
git mv <file_from> <file_to>
```
**Viewing the commit history**
```
git log <Options>
```
**Options:**

`--patch | -p`  > shows the diference (the patch outputs)

`-2` > Show only the last two entries

`--stat`  > abbreviated stats dor each commit

:rotating_light: search for another log options and log filters when necessary 

### Undoing things

**Overwrites your previous commit**
```
git commit --amend
```

**Unstaging a Staged file**

```
git reset HEAD <file>
```

**Unmodifying a modified file**

```
git checkout --<file>
```
:rotating_light: Git just replace that file with the most recently-committed version

### Remotes

**Showing your remotes**
```
git remote <Options>
```
**Options:**

`-v`  > Shows the URLs

**Add a new remote GIT repository**
```
git remote add <shortname> <url>

```
**Fetch to download the data to your local repository**
```
git fetch <shortname>
```
**Fetch data and merge data from the origin repository** 
```
git pull
```
**Pushing your remotes**
```
git push <remote> <branch>
```
**Inspecting a remote**
```
git remote show <remote>
```
**Rename remotes**
```
git remote rename <remote_from> <remote_to>
```
**Removing remotes**
```
git remote remove <remote>
```
```
git remote rm <remote>

```
### Tagging**
*Creating release points v1.0... v2.0*

**listing your tags**
```
git tag
```
**with a pattern**
```
git tag -l <Pattern>
```
**Creating a tag**

- Lightweight - pointer to a specific commit
```
git tag <version>
```
- Annotaded - stored as full objects in the git database
```
git tag -a <version> -m "<tagging-message>"
```
**Inspecting a tag**
```
git show <tag>
```
**Tagging later**

*with te commit checksum (or part of it) - git log*
```
git tag -a <version> <checksum>
```
**Sharing tags**

:rotating_light: the *git push* command doesn't transfer tags to remote server

```
git push <remote> <Options>
```
Options:

`<version>` > Push this version

`--tags` > Push all versions

**Delete tag**
```
git tag -d <version>
```
```
git push <remote> -d <version>
```
**Checking tags**
```
git checkout -b <branchName> <version>
```
### Alias
```
alias.<command> '<new alias>'
```
## Git branching

**Creating a branch**
```
git branch <newBranch>
```
**Switch a branch**
```
git checkout <branch>
```
**Creating and switch to a branch**
```
git checkout -b <newBranch>
```
**Merging branches**
```
git merge <branch>
```
:rotating_light: after merging you can delete the branch you worked before

**Merge conflicts**

After a merge to see the conflict use `git status`, you can resolve manually changing the files and using `git add` or you can resolve graphically using `git mergetool`

**Branch management**
```
git branch <Options>
```
Options:
` ` > Show all branches
`-v` > Show last commit of each branch
`--merged` >   Show the branches you have merged
`--no-merged` > Show the branches you haven't merged

**Remote tracking branch names**

```
git ls-remote <remote>
```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```

```
