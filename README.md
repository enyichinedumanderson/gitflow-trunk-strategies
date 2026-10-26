# Branching Strategies: GitFlow vs Trunk

Compared GitFlow and Trunk-based branching, managed a pull request lifecycle, and resolved a merge conflict.

## Commands Covered

```bash
git checkout -b develop
git checkout -b feature/user-login
gh pr create --base develop --title "feat: user login scaffold"
gh pr merge --squash --delete-branch
git merge main
```
