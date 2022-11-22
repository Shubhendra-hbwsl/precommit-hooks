## Installation


1. Install pip3 `sudo apt install python3-pip`
2. Install pre-commit package `pip install -U pre-commit`
3. Clone this repo
4. Copy the `.git-commit-message-template to your home directory` for using the template in all git projects.
`cp .git-commit-message-template ~/.git-commit-message-template`
5. Configure the git message template globally by running `git config --global commit.template ~/.git-commit-message-template`
6. Copy all the contents of `git_hooks` dir to `.git/hooks/` for using the hooks, `cp git_hooks/* .git/hooks/`.
7. Copy `.pre-commit-config.yaml` to your project dir

> Note: You have to repeat only the `Step. 6` and `Step. 7` for every new repo, as hooks are located in .git/hooks which is not version controlled.
