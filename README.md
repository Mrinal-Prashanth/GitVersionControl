
#  Git Version Control – What I learned

##  Based on: [Git Tutorial for Beginners - GitHub Version Control](https://www.youtube.com/watch?v=PWqS4NBhEY8)

---

##  What is Git?

Git is a **version control system** that helps developers:
- Track and manage changes in code
- Collaborate with others on projects
- Maintain a history of file changes

---

##  Basic Git Commands

###  `git init`
Initializes a new Git repository in your current directory.

```bash
git init
```

---

###  `git status`
Shows the status of changes (tracked, untracked, staged).

```bash
git status
```

---

###  `git add <file>`
Stages changes (files) to be committed.

```bash
git add file.txt
# or to add all files:
git add .
```

---
---

###  `git rm --cached <file>`
Stages changes (files) to be removed.

```bash
git rm --cached file.txt

```
###  `git commit -m "message"`
Saves the staged changes to the repository with a message.

```bash
git commit -m "First change"
```

---

###  `git log`
Shows the commit history.

```bash
git log
```

---

###  `git diff`
Shows the differences between modified and committed files.

```bash
git diff
```

---

###  `git branch <name>`
Creates a branch.

```bash
git branch branch1
```

---
###  `git checkout`
Switches branches or restores files.

```bash
git checkout branch1   # Create and switch to new branch
git checkout main             # Switch back to main
```
---

###  `git branch`
Lists branches.

```bash
git branch
```

---

###  `git merge`
Merges one branch into another.

```bash
git merge branch1
```

---

###  `git clone`
Clones a remote repository to your local machine.

```bash
git clone https://github.com/FIREBOYY11/GitVersionControl
```

---

###  `git pull`
Pulls the latest changes from a remote repository.

```bash
git pull origin main
```

---

###  `git push`
Pushes your changes to the remote repository.

```bash
git push origin main
```

---

### Create a new repository via cmd

```bash
git init
git add README.md
git commit -m "First change"
git remote add origin https://github.com/FIREBOYY11/GitVersionControl.git
git push -u origin main
```

### Upload an exisisting repository via cmd

```bash
git remote add origin https://github.com/FIREBOYY11/GitVersionControl.git
git push -u origin main
```

---
##  Key Concepts

- **Repository**: Where your project's history is stored.
- **Working Directory**: Where you edit files.
- **Staging Area**: Where you prepare files to be committed.
- **Commit**: A snapshot of changes.

---

##  Git Workflow

1. Modify files
2. Stage changes with `git add`
3. Commit with `git commit`
4. Push to remote with `git push`

---

##  Collaboration Basics

- Use `clone` to download a repo
- Use `branch`, `merge`, and `pull` to collaborate
- Use `push` to upload your changes

---

##  Best Practices

- Write clear commit messages
- Commit frequently
- Use branches for new features
- Pull before you push

---
