# cli-bash-tool
CLI tool to enable shorthand commands for tedious things tasks

## Setup

### Enable alias
Add the `sotr` alias to your bashrc file
```
nano ~/.bashrc
alias sotr=". /path/to/cli/clifile"
```

### Edit paths
Create a file called `secrets`. Add the following,
```bash
project=""
cli=""
reddit=""
frontend=""
backend=""
main_website=""
main_ssh_login=""
jenkins_ssh_login=""
main_login_tip=""
```

Fill these in with your variables.

### Yay!
Now you can use `sotr command` in the terminal.

Type `sotr -h` for commands.
