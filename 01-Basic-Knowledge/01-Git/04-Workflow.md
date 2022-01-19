# Workflow

## Download commits, files, and refs

### 1. Git Fetch

:rotating_light: Fetching is what you do when you want to see what everybody else has been working on. ... This makes fetching a safe way to review commits before integrating them with your local repository.

- Use `git fetch <remote>` or `git fetch <remote> <branch>` to download the data to your local repository.
- Switch branches to validate the changes `05-Branching.md`
- Merge branches after validating the changes `05-Branching.md`

### 2. Git Pull
*fetch the data and merge data from the origin repository*

```
git pull
```

### Checking the status of your file
```
git status <Options>
```
**Options:**

`-s`  > Simplified status

### Tracking/Staging files
```
git add <Options> 
```
**Options:**

`<file>`  > Add file to staged area

`*` | `-A` | `--all` > Add all files to staged area

:rotating_light: Checking Unstaged/Staged changes
```
git diff
```

### Committing your changes**
```
git commit <Options>
```

**Options:**

`-v`  > Also puts the diff of your change in the editor

`-m "text"`  > Commit message inline

`-a`  > Skip the staging area

:rotating_light: Checking Staged/Committed changes
```
git diff --staged
```

:rotating_light: Checking  git diff in an External Tool *Include a nice description of changes when you submit your pull request (PR)*

```
git difftool
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

**Removing files from tracked files**
```
git rm <Options>
```
**Options:**

`<file>`  > remove file from tracked

`--cached <file>`  > remove file from staged

`<pattern>`  > remove files with this pattern

**Moving/Renaming files**
```
git mv <file_from> <file_to>
```

### Pushing to your remote

```
git push
```
