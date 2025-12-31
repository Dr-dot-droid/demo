## Git Usage

Git is a **distributed version control system** used to track changes in source code during software development. It allows multiple developers to collaborate efficiently on the same project.

### 1. Initialize a Repository

Create a new Git repository:

```bash
git init
```

### 2. Clone a Repository

Copy an existing remote repository to your local machine:

```bash
git clone <repository_url>
```

### 3. Check Repository Status

View the current state of files in the working directory:

```bash
git status
```

### 4. Add Files to Staging Area

Stage files for the next commit:

```bash
git add <file>
git add .
```

### 5. Commit Changes

Save staged changes with a message:

```bash
git commit -m "Commit message"
```

### 6. View Commit History

Check previous commits:

```bash
git log
```

### 7. Create and Switch Branches

Create or switch branches for feature development:

```bash
git branch <branch_name>
git checkout <branch_name>
git checkout -b <branch_name>
```

### 8. Merge Branches

Merge another branch into the current branch:

```bash
git merge <branch_name>
```

### 9. Pull Updates from Remote Repository

Fetch and merge changes from a remote repository:

```bash
git pull
```

### 10. Push Changes to Remote Repository

Upload local commits to a remote repository:

```bash
git push
```

### 11. Resolve Conflicts

When conflicts occur, manually edit the conflicting files, then:

```bash
git add <file>
git commit
```

### 12. Delete a Branch

Remove a branch when it is no longer needed:

```bash
git branch -d <branch_name>
```
