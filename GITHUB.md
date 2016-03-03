# Create

Creat new git repository inside directory

```bash
git init
```

# Inspect

Show the files youve changed.

```bash
git status
```

See changes to tracked files.

```bash
git diff
```

See history of commits

```bash
git log
```

See who changed something

```bash
git blame <file>
```

# Branches

Switch branch

```bash
git checkout <branch>
```

Create new branch based off current branch

```bash
git branch <branchname>
```

Create new branch and switch to it

```bash
git checkout -b <branchname>
```

Create new branch with no files

```bash
git checkout --orphan <branch>
```

Delete branch

```bash
git branch -D <branch>
```

Rename current branch

```bash
git branch -m <branch>
```

# Updating & Publishing

Show remotes

```bash
git remote -v
```

Add remote 

```bash
git remote add <remotename> <git@url>
```

Remove remote 

```bash
git remote remote <remotename>
```

Pull (alias for fetch +_ merge)

```bash
git pull <remotename> <branchname>
```

Fetch remote branches

```bash
git fetch <remotename> <branchname>
```

Push changes

```bash
git push <remotename> <branchname>
```

Push your code and overwrite anything else

```bash
git push --force <remotename> <branchname>
```

Merge branch into your current one

```bash
git merge <branchname>
```

Reset all your code to a certain commit (useful with `git log`)

```bash
git reset --hard <commitshanumber>
```

Reset all your code to latest of branch

```bash
git reset --hard HEAD
```

