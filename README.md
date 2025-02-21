# 🖥️ GIT COMMANDS CHEAT SHEET

## 🔧 Set configuration values for your username and email
```sh
git config --global user.name "YOUR NAME"
git config --global user.email "YOUR EMAIL"
```

## 📌 Set default branch to main
```sh
git config --global init.defaultBranch main
```

## ❓ Get help on a command
```sh
git help COMMAND
git COMMAND -h
```

## 🏗️ Initialize a new git repository
```sh
git init
```

## 📥 Clone a repository
```sh
git clone REPOSITORY_URL
```

## 📂 Add files to the staging area
```sh
git add FILE      # Add a specific file
git add --all     # Add all file changes
git add -A        # Add all file changes
git add .         # Add all file changes
```

## 🔍 Check the unstaged changes
```sh
git diff
```

## ✅ Commit the staged changes
```sh
git commit -m "MESSAGE"
```

## ♻️ Reset staging area to the last commit
```sh
git reset
```

## 📌 Check the state of the working directory and the staging area
```sh
git status
```

## 🗑️ Remove a file from the index and working directory
```sh
git rm FILENAME
```

## ✏️ Rename a file
```sh
git mv OLD_NAME NEW_NAME
```

## 📜 List the commit history
```sh
git log
```

## 🌿 List all the local branches
```sh
git branch
```

## 🌱 Create a new branch
```sh
git branch BRANCH_NAME
```

## ✏️ Rename the current branch
```sh
git branch -m NEW_BRANCH_NAME
```

## 🗑️ Delete a branch
```sh
git branch -d BRANCH_NAME
```

## 🔄 Switch to another branch
```sh
git switch BRANCH_NAME
```

## 🔀 Merge specified branch into the current branch
```sh
git merge BRANCH_NAME
```

## 🌍 Create a connection to a remote repository
```sh
git remote add NAME REPOSITORY_URL
```

## 🚀 Push the committed changes to a remote repository
```sh
git push REMOTE BRANCH
```

## 📥 Download the content from a remote repository
```sh
git pull REMOTE
