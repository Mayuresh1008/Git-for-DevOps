# **Git Commands for DevOps**

## **Basic Linux Commands**
- `ls` → List files and directories.
- `mkdir git-for-devops` → Create a new directory.
- `cd git-for-devops/` → Navigate into the directory.
- `vim hello-dosto.txt` → Open or create a file in Vim editor.
- `cat hello-dosto.txt` → Display contents of a file.
- `rm hello-dosto.txt` → Remove a file.
- `ls -1` → List files in a single column.
- `ls -l` → List files with detailed information.
- `ls -a` → Show hidden files.

## **Initializing and Checking Git Repository**
- `git init` → Initialize a new Git repository.
- `git status` → Check the status of the working directory and staging area.

## **Working with Files**
- `touch file1.txt file2.txt` → Create multiple empty files.
- `rm hello-dosto.txt` → Delete a file.
- `rm file2.txt` → Remove a specific file.
- `git restore file2.txt` → Restore an uncommitted file.

## **Staging and Unstaging Files**
- `git add nibbi.txt` → Add a file to the staging area.
- `git add file2.txt` → Stage a specific file.
- `git add file1.txt` → Stage another file.
- `git rm --cached file1.txt` → Unstage a file.

## **Committing Changes**
- `git commit -m "adding files"` → Commit staged changes with a message.
- `git commit -m "added new changes to file2"` → Commit additional changes.

## **Managing Files in Git**
- `touch f1.txt f2.txt` → Create two files.
- `git add f1.txt f2.txt` → Stage multiple files.
- `git rm --cached f2.txt` → Unstage a specific file.

## **Configuring Git**
- `git config --global user.name "Mayuresh1008"` → Set Git global username.
- `git config --global user.email "mayuresh.patil1008@gmail.com"` → Set Git global email.

## **Tracking and Committing Changes**
- `vim file2.txt` → Edit a file using Vim.
- `git add file2.txt f2.txt` → Stage modified files.
- `git commit -m "added new changes to file2"` → Commit changes with a message.

## **Viewing Command History**
- `history` → Display a list of previously executed commands.

