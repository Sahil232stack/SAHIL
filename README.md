# SAHIL
Author_ SAHIL KOKITKAR
Git & GitHub Roadmap for Freshers (3-5 LPA Placement Focus)

---

1️⃣ Basics of Version Control

* Why Git?

  * Tracks code changes, collaborates with teams, manages projects.
* Types of Version Control:

  * Local VCS, Centralized VCS, Distributed VCS (Git is distributed).
* Key Concept: Commits, branches, merge, repository, remote.

---

2️⃣ Git Fundamentals

Setup:

```
git config --global user.name "Your Name"
git config --global user.email "you@example.com"
```

Common Commands:

| Command                 | Purpose                    |
| ----------------------- | -------------------------- |
| git init                | Create a local repo        |
| git clone <url>         | Copy a remote repo locally |
| git status              | Check repo status          |
| git add <file>          | Stage changes              |
| git commit -m "message" | Save changes               |
| git log                 | View commit history        |
| git diff                | See changes                |
| git branch              | List branches              |
| git checkout <branch>   | Switch branch              |
| git merge <branch>      | Merge branches             |
| git pull                | Get updates from remote    |
| git push                | Push commits to remote     |

---

3️⃣ Branching Basics

* Default branch: main or master
* Feature branch: git checkout -b feature1 → develop new feature
* Merge workflow: Feature branch → main branch → push to remote

---

4️⃣ GitHub Basics

* Cloud-based Git repo hosting
* Key Features: Repositories, Pull Requests (PR), Issues, Actions
* Account Setup: Create free account → set SSH/HTTPS key → connect with local Git

Basic GitHub Workflow:

1. git clone <repo-url> → local copy
2. Make changes → git add → git commit
3. git push origin <branch> → update remote
4. Create Pull Request to merge changes (if collaborating)

---

5️⃣ Collaboration Concepts

* Fork: Copy someone else’s repo to your account
* Pull Request (PR): Request to merge your changes into original repo
* Issues: Track bugs or features
* Conflict Resolution: Fix merge conflicts using git merge or git rebase

---

6️⃣ Advanced but Important for Placements

* git stash → temporarily save changes
* git revert → undo a commit safely
* git reset → remove commits (use carefully)
* git remote -v → view remote URLs
* Difference between git pull vs fetch

---

7️⃣ Tips for 3–5 LPA Placement

1. Practical knowledge matters: Setup repo, clone, commit, push, create branch, PR
2. Mini-project: Keep a GitHub repo with 2–3 small Java projects
3. Explain in interviews:

   * Difference between Git and GitHub
   * Difference between git pull and git fetch
   * How branching and merging works
4. Focus on practical workflow confidence, not deep internals

