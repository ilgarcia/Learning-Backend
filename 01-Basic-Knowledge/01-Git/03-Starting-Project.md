# Starting a project

## The Command Line
there is a lot of ways to use Git, there are the original command-line tools, and there ara many graphical user interfaces (GUIs) of varying capabilities.

### Getting Help
```
git help <verb>
```
```
git <verb> <Options>
```
**Options:**

`--help`  > Getting help

`-h`  > Getting help

## Getting a git repository

### 1. Take a local directory and turn it into a git repository

- First, initialize `git init` the repository.
- Create a remote repository somewhere like https://github.com/.
- Add the remote URL to your local git repository with `git remote add origin <URL>`. This stores the remote URL under a more human-friendly name, `origin`.
- Shape your history into at least one commit by using `git add` to stage the existing files, and `git commit` to make the snapshot.
- You can push to the remote and set up the tracking relationship with `git push -u origin master`

### 2. Clone an existing Git repository from elsewhere**
```
git clone <url> (<directory name>)
```
:rotating_light: You have tree options to clone your repository
- HTTPS - Connect before cloning 
- SSH - Create a SSH key before cloning
- GitHub CLI - GitHub Terminal

**Ignoring files**
create a file named `.gitignore` 

<p>
  <a href="https://github.com/github/gitignore">File examples for dozens of projects and languages</a>
</p>

### Creating alias
```
alias.<command> '<new alias>'
```
