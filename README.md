This project is a set of useful scripts for team collaboration using git.

# Workflows #

## Personal Branch ##

1. Create a branch.
2. Work, commit, &c.
3. Arrange changes logically using `git local-rebase` (optional)
4. `git upstream-rebase`
5. `git upstream-push`

## Shared Branch ##

1. Create a branch.
2. `git share-branch`
3. Use the Personal Branch workflow. Repeat.
8. Create a branch from the branch you are merging into (usually `origin/master`).
9. `git merge origin/${shared_branch_name}`
10. Handle any conflicts.
11. `git upstream-push`
