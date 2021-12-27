# The COmmand Line

there is a lot of ways to use Git, there are the original command-line tools, and there ara many graphical user interfaces (GUIs) of varying capabilities.

## Git Setup

> git config

Variables can be stored in three different places:

**--system**

`/etc/gitconfig`

**--global**

`~/.gitconfig or ~/.config/git/config`

**--local**

`.git/config`

To view all of your settings and where they are coming from use:

> git config --list --show-origin

**Change config**

> git config <--system|--global|--local> <new config>

**Getting Help**

> git help <verb>
>
> git <verb> --help or -h

## GIT Basics

**Getting a git repository**

1. Take a local directory and turn it into a git repository
> git init

2. Clone an existing Git repository from elsewhere
> git clone <url> (<directory name>)

**Checking the status of your files**
> git status
>
> git status -s

**Tracking/Staging files** 
> git add <file> | * | -A | --all

**Ignoring files**

create a file named `.gitignore` 

```
Search the rules for the patterns you can put in the file .gitignore
File examples for dozens of projects and languages
https://github.com/github/gitignore
```

