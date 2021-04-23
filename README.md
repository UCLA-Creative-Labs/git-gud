# git-gud

Welcome to Creative Lab's Spring 2021 Field Notes git workshop.

## Gitting Started

To get started, clone the repository.

```sh
$ git clone https://github.com/UCLA-Creative-Labs/git-gud.git
```

## status

Run `git status` whenever you are lost or need more information on your 
repository!

```sh
$ git status
```

### Example Output

```sh
On branch main
Your branch is up to date with 'origin/main'.

Changes to be committed:
  (use "git restore --staged <file>..." to unstage)
	modified:   README.md

Untracked files:
  (use "git add <file>..." to include in what will be committed)
	manifesto.txt
```

## checkout

Run `git checkout <branch_name>` to move to another branch. 

### Tips

Run `git checkout -b <branch_name>` to *create* and *checkout* a branch.

> The branch name that you create should reflect desired change

```sh
$ git checkout -b manifesto
```

## add

Run `git add` when you want to add changes to a staging area. Files in the
staging are **"ready to be commited"**.

### Tips

Usually, you can get away with just staging everything that you changed. 
While not approved by `git purists`, it's a quick and easy way to utilize
git without any of the frustratioin.

```sh
$ git add .
```

## commit

Run `git commit -m <message>` when you want to commit changes in the 
staging area. These commits are "checkpoints" that should have a descriptive
message that describes the relevant changes.

### Example

If the changes made were to the `manifesto.txt` and was to add a table of 
contents to the file, an appropriate commit message would be:

```sh
$ git commit -m "add table of contents to manifesto"
```

## push

Run `git push` to upload your commits to a shared repository.

```sh
$ git push
```