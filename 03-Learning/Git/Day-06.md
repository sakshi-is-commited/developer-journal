## Git Restore
It is a focused command used to undo uncommitted local changes by restoring files in your working directory or staging area to a previous known state.

## Git Reset
It is a powerful command used to undo local changes by moving the current branch pointer(HEAD) to a specific previous commit.

## Soft Reset
It is a command that undoes recent commits while preserving all your local code changes directly in the staging area.

## Mixed Reset
It is the default operational mode for the git reset command, meaning it runs automatically if you use git reset without specifying any flags. It rewinds your current branch pointer (HEAD) to a specific prior commit and clears the staging area (index) while completely preserving your actual file medications in your local working directory.

## Hard Reset
It is a destructive Git command that rewinds your current branch history to a specific commit while completely discarding all uncommitted changes and subsequent commits from your working directory and staging area.

## Git Revert
It is a safe, forward-moving undo command that reverses the changes of a specific past commit by creating an entirely new "inverse" commit.

## Reset vs Restore
The primary difference is their scope: git reset manipulates commit history and branch pointers, while git restore safely discards uncommitted file-level changes in your working directory or staging area.

## Reset vs Revert
The main difference is that git reset rewrites history by moving the branch pointer backward, while git revert preserves history by adding a new commit that safely inverses changes. Because of this, you should only use git reset for local, unpushed commits, and use git revert when changes have already been shared with a team on a remote branch.

## When to use each
Use git restore for uncommitted file-level edits, git reset for erasing or re-organizing local commits, and git revert for safely undoing pushed, public history.