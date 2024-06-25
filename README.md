Add your names to the modify file. Fix conflicts and raise a pull request.

To start with it, you need to reset to the latest main. Since your main might have too many commits not present in main.

Fetch updates the git index with the latest changes from main, doesn't update your branches.
Reset, resets to the fetched main.

```bash
git fetch
git reset origin/main --hard
```