# Git Setup

## Installing Git

https://git-scm.com/

## Show all config options

```
git config
```

### Variables can be stored in three different places:
> **--system**
> 
> /etc/gitconfig

> **--global**
> 
> ~/.gitconfig or ~/.config/git/config

> **--local**
> 
> .git/config

**To view all of your settings and where they are coming from use:**
```
git config --list --show-origin
```

**Change config**
```
git config <--system|--global|--local> <config.name> <new config>
```