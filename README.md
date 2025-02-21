# 🖥️ GIT COMMANDS CHEAT SHEET

## 🔧 Configuration Commands
| Command | Description |
|---------|-------------|
| `git config --global user.name "YOUR NAME"` | Set global username |
| `git config --global user.email "YOUR EMAIL"` | Set global email |
| `git config --global init.defaultBranch main` | Set default branch to `main` |
| `git config --global --list` | List global configurations |

## ❓ Help Commands
| Command | Description |
|---------|-------------|
| `git help COMMAND` | Get help on a specific command |
| `git COMMAND -h` | Get short help for a command |

## 🏗️ Repository Setup
| Command | Description |
|---------|-------------|
| `git init` | Initialize a new Git repository |
| `git clone REPOSITORY_URL` | Clone an existing repository |

## 📂 Staging Files
| Command | Description |
|---------|-------------|
| `git add FILE` | Add a specific file to staging |
| `git add --all` / `git add -A` / `git add .` | Add all changes to staging |

## 🔍 Checking Changes
| Command | Description |
|---------|-------------|
| `git diff` | Show unstaged changes |
| `git status` | Check the state of the working directory |

## ✅ Committing Changes
| Command | Description |
|---------|-------------|
| `git commit -m "MESSAGE"` | Commit staged changes with a message |

## ♻️ Resetting Changes
| Command | Description |
|---------|-------------|
| `git reset` | Reset staging area to the last commit |

## 🗑️ Removing and Renaming Files
| Command | Description |
|---------|-------------|
| `git rm FILENAME` | Remove a file from Git |
| `git mv OLD_NAME NEW_NAME` | Rename a file |

## 📜 Branching
| Command | Description |
|---------|-------------|
| `git branch` | List all local branches |
| `git branch BRANCH_NAME` | Create a new branch |
| `git branch -m NEW_BRANCH_NAME` | Rename the current branch |
| `git branch -d BRANCH_NAME` | Delete a branch |

## 🔄 Switching & Merging Branches
| Command | Description |
|---------|-------------|
| `git switch BRANCH_NAME` | Switch to another branch |
| `git merge BRANCH_NAME` | Merge specified branch into current branch |

## 🌍 Remote Repository
| Command | Description |
|---------|-------------|
| `git remote add NAME REPOSITORY_URL` | Connect to a remote repository |
| `git push REMOTE BRANCH` | Push committed changes to a remote repository |
| `git pull REMOTE` | Fetch and merge changes from a remote repository |

## 🛠️ Additional Commands That Might Help

### 🔄 Undoing & Fixing Mistakes
| Command | Description |
|---------|-------------|
| `git checkout -- FILE` | Discard changes in working directory |
| `git restore FILE` | Restore a file to the last committed state |
| `git reset --soft HEAD~1` | Undo the last commit but keep changes staged |
| `git reset --hard HEAD~1` | Undo the last commit and remove changes |

### 📜 Viewing Commit History
| Command | Description |
|---------|-------------|
| `git log --oneline` | Show commit history in one line per commit |
| `git log --graph --decorate --all` | Show a visual graph of commits |

### 📌 Stashing Changes (Temporarily Save Work)
| Command | Description |
|---------|-------------|
| `git stash` | Save uncommitted changes for later |
| `git stash list` | Show saved stashes |
| `git stash pop` | Restore the most recent stash |
