* what is a branch?
- A branch in Git is simply a lightweight movable pointer to one of the commits.

* why are branches useful?
- Because they are incredibly lightweight making branching operations nearly instantaneous, and switching back and forth branches generally just as fast.

* What is a branch pointer?
- It is a lightweight movable label that points directly to a specific commit.

* why are branches lightweight?
- Because they are simple text files containing a single 40-character SHA-1 commit hash. They do not duplicate files, copy directories, or store project history within themselves.

* What does HEAD point to?
- HEAD points the references of your current active branch or workspace.

* What happens when switching branches?
- When you switch branch, your working directory and codebase state change to match the exact history of the target branch

* difference between  git branch, switch and checkout
- git brach creates or lists branches without moving you to them, git switch is a modern command dedicated entirely to changing branches, and git checkout is a legacy command that can switch branches, navigate commits, and restore files.