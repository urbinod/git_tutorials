# Git Tutorials

## Create new repository

```http
  https://github.com/new
```

# Following are the steps

### step 1 (Download into my local from internet repository (git clone <url>)

```http
  git clone https://github.com/urbinod/git_command_tutorials.git

```

### step 2 (List all the files into current directory)

```http
  $ ls
```

### step 3 (Move into directory)

```http
  $ cd foldername
```

### step 4 (Create new file from terminal using touch)

```http
  $ touch product.html
```

### step 5 (Now we need to commit - Save the snapshot of the file)

```http
  $ git commit -m "message"
```

### step 6 (Now we need to commit - commit all files)

```http
  $ git commit -am "message"
```

### step 7 (To see what is currently happening in my git repository)

```http
  $ git status
```

### step 8 (check whether the your branch is up to date to master before push)

```http
  $ git pull
```

### step 9 (Now we need to commit - Save the snapshot of the file)

```http
  $ git push
```

#### When someone changes the same file eg: product.html and you are modifying the same file when we git pull, we will have conflict. Make change in conflict file to which file you wants and commit the file as $ git commit -am “messge” and git push

#### git log (show the list of commit id , author, date, who have added)

#### git reset (Git reset in effect will take the current state of the repository and revert it back to an older state of the repository)

```http
  $ git reset
  either $ git reset - - hard <commit>
  or either $ git reset - - hard origin/master
```

## Branching

| Command                                            | Description                                                                  |
| -------------------------------------------------- | ---------------------------------------------------------------------------- |
| git branch                                         | List branches (the asterisk denotes the current branch). To get out, press Q |
| git branch -a                                      | List all branches (local and remote)                                         |
| git branch [branch name]                           | Create a new branch                                                          |
| git branch -d [branch name]                        | Delete a branch                                                              |
| git push origin --delete [branch name]             | Delete a remote branch                                                       |
| git checkout -b [branch name] origin/[branch name] | Clone a remote branch and switch to it                                       |
| git branch -m [old branch name] [new branch name]  | Rename a local branch                                                        |
| git checkout [branch name]                         | Switch to a branch                                                           |
| git checkout -                                     | Switch to the branch last checked out                                        |
| git checkout -- [file-name.txt]                    | Discard changes to a file                                                    |
| git merge [branch name]                            | Merge a branch into the active branch                                        |
| git merge [source branch] [target branch]          | Merge a branch into a target branch                                          |
| git stash                                          | Stash changes in a dirty working directory                                   |
| git stash clear                                    | Remove all stashed entries                                                   |
