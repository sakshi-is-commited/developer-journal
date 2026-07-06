## Merge
It is used to combine changes from two or more development branches into single branch.

## Fast-Forward Merge
This occurs if the destination branch (main) has not received any new commits since you created your feature-branch. Git doesn't create a new commit; it simply moves the main branch pointer forward to match your branch tip.

## Three-way Merge
This occurs if both branches have diverged (e.g. someone else updated main while you worked on your feature). Git compares the snapshots of both branch tips with their shared ancestors to create a brand-new merge commit that joins the histories together.

## Rebase
This is used to integrate changes from one branch into another by moving the entire feature branch so it begins at the tip of the target branch.

## Merge Commit
It is a special type of commit in Git that unites the history of two separate branches. Unlike regular commits, a merge commit typically has two or more parent commits, representing the pint where the diverging branches are joined together.

## Advantages of Merge
- It is non-destructive operation that preserves the complete, chronological history of your repository without altering existing commits
- Preserves comple context
- Safe for shared Branches
- Merge resolves conflicts once during the merge operation while preserving both branch histories.

## Advantages of Rebase
- It creates a clean, linear project history by moving your feature branch commits to the tip of the target branch.
- No branching visual cutter
- Sequential order
- Easier Tracing

## Disadvantages of Rebase
- It fundamentally rewrites your commit history. If done on shared or public branches, this can destroy work, disrupt team members, and cause major conflicts.
- Lost work on Shared Branches
- Require force pushing
- During a rebase, conflicts may need to be resolved for each commit being replayed, which can be more time-consuming than resolving conflicts during a single merge.

## When not to Rebase?
Never rebase commits that have already been pushed to a shared remote repository.
