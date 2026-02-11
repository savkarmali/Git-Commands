**Basic Git Commands**

- **Initialize a repository**  
  `git init`  
  Creates a new Git repository in your project folder.

- **Clone a repository**  
  `git clone <repo-url>`  
  Downloads a remote repo to your local machine.

- **Check status**  
  `git status`  
  Shows changes staged, unstaged, and untracked.

- **Add files to staging**  
  `git add <filename>` or `git add .`  
  Stages changes for commit.

- **Commit changes**  
  `git commit -m "your message"`  
  Saves staged changes with a message.

- **View commit history**  
  `git log`  
  Lists all commits in the current branch.

---

### 🌿 **Branching & Merging**

- **Create a new branch**  
  `git branch <branch-name>`

- **Switch branches**  
  `git checkout <branch-name>`  
  Or use `git switch <branch-name>` (modern syntax)

- **Merge branches**  
  `git merge <branch-name>`  
  Merges the specified branch into the current one.

- **Delete a branch**  
  `git branch -d <branch-name>`

---

### 🌐 **Remote Repositories**

- **Add a remote**  
  `git remote add origin <repo-url>`

- **Push changes**  
  `git push origin <branch-name>`

- **Pull changes**  
  `git pull origin <branch-name>`

- **Fetch updates**  
  `git fetch`  
  Downloads changes without merging.

---

### 🔍 **Advanced & Useful**

- **View differences**  
  `git diff`  
  Shows changes between commits, branches, or working directory.

- **Stash changes**  
  `git stash`  
  Temporarily saves changes not ready to commit.

- **Apply stashed changes**  
  `git stash apply`

- **Undo last commit (keep changes)**  
  `git reset --soft HEAD~1`

- **Remove file from staging**  
  `git reset <filename>`

