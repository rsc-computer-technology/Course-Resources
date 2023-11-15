# Git Commands 

The following are commands that can be useful in troubleshooting issues with git.

| Command | Description |
|-----|-----|
| `git version` | This will tell you what version of git is installed. |
| `git config --global user.name` | This will show you the name of the user for all git repos. |
| `git config --global user.email` | This will show you the email address of the user for all git repos. |
| `git remote` | This will show you the name of the remote repository. e.g., `origin` |
| `git remote -v` | This will allow you to see what the URL is set for the fetch and push commands. |
| `git remote get-url --all origin` | This will show you the URL of the remote repository. It may also include the username and password used to log in, which can be used to double check that it is using what is expected. |
| `git remote set-url <Remote Name> <URL>` | This will set the URL for the remote repo. Replace the `<Remote Name>` with the name of the repo found with the `git remote` command. Replace the `<URL>` with the URL of your repo on GitHub. |
