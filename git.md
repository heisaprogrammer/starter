# Undo a git merge that has been pushed to the server
```
git reset --hard [sha-commit-before-merge]
git push [origin] [branch] --force
```

This will undo the merge and any commits after the merge, so this is useful if you catch your mistake before any more commits happens.

source: [Coderwall](https://coderwall.com/p/o0krbw/undo-a-git-merge-that-has-been-pushed-to-the-server)
