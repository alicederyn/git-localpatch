# git-localpatch

Work-in-progress. Add the following to your `.gitconfig`:

```text
[filter "patch"]
  clean = /path/to/clean-patch %f %f.patch
  smudge = /path/to/smudge-patch %f %f.patch
```
