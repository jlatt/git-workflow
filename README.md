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
4. `git merge-into origin/master`
5. Handle any conflicts.
6. `git push origin HEAD:master`
