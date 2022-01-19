# Tagging
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
- Annotated - stored as full objects in the git database
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