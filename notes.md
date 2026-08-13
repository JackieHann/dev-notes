# How do I...

<!-- One entry per thing I had to look up. Newest at the top.
     Problem as a question, the command, why the flags, where I hit it. -->

## Find all files over 100MB in a directory tree
```bash
find . -type f -size +100M
```
- `-type f` = files only, otherwise directories match too
- Used when hunting for what was filling ~/projects
