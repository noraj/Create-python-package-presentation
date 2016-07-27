## Git tips

If the package code source is hosted on a Git repository:
- a `.gitignore` can be added (ex: GitHub Python [gitignore](https://github.com/github/gitignore/blob/master/Python.gitignore) to avoid uploading `dist/` or `build/` folders to the remote Git repository.
- If the Git remote repository is GitHub `git tag 0.1 -m "message"` & `git push --tags origin master` can be used to generate and host package

**Warning**: To use `git tag` on GitHub there must be only one tool per repository (no multi-tools repository).
