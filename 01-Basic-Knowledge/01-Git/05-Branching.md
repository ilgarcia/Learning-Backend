# Branching

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
:rotating_light: after a fetch you can create a new branch and merge this fetch

**Merging branches**
```
git merge <branch>
```
:rotating_light: after merging you can delete the branch you worked before
```
git branch -d <branch>
```

**delete branch remotely**

git push origin --delete remoteBranchName

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

## Git Rebase
*Istead of merging you can use `git rebase`, in favour of the desire to achieve a linear history.*

```
git rebase
```

## Remotes

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

