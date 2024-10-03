# COMP 290 Commands and References

Based on popular demand, this short document summarizes the shell commands from **COMP 290** that are useful!

### Basic Shell Commands

| Command | Description |
| --- | :----- |
| `pwd` | Lists the shell's current working directory. |
| `cd <filepath>` | Change the current working directory to the supplied filepath. |
| `ls` | Lists the files in the current working directory.<br>- `-a`: Shows hidden files.<br>- `-l`: Shows details about files. |
| `clear` | Clears the current terminal window. |
| `echo <text or env var>` | Repeats the supplied text to the console. |
| `echo <text> > <filepath>` | Overwrite (or create) a file at the filepath with the text contents.<br>*Note: Environment variables should be preceded by `$`. For example: `echo $PATH`.* |
| `echo <text> >> <filepath>` | Append to (or create) a file at the filepath with the text contents. |
| `cat <filepath>` | Print the contents of a file at the filepath to the shell. |
| `export <env var>=<value>` | Saves a new value to an environment variable. |

### Package Managers and `fzf`

| Command | Description |
| --- | :----- |
| `brew install <pkg>` | Uses homebrew (Mac package manager) to install external programs. |
| `winget instal <pkg>` | Uses winget (Windows package manager) to install external programs. |
| `fzf` | Opens the fzf fuzzy finding tool. |


### Git Commands

| Command | Description |
| --- | :----- |
| `git init` | Creates a git repository at the current working directory. |
| `git add <filepath \| .>` | Adds modified files to the git's staging area (adds file to the next commit). |
| `git commit -m <message>` | Creates a git commit with a supplied commit message. |
| `git status` | Shows the current changes made in a repository and the state of the current draft commit. |
| `git log` | Shows the git history.<br>- `--all`: Shows the entire git history.<br>- `--decorate`: Decorates each commit with more information.<br>- `--oneline`: Displays commit information on one line.<br>- `--graph`: Displays the history in a graph structure.<br>*Remember the "a dog" acronym!* |
| `git checkout <id>` | Changes the git repository to the state of the repository at the commit with the provided commit id. |
