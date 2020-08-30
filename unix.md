## grep / find

* Search for a pattern in a directory:

```bash
## flags for: recursive, line number, whole word
grep -rnw '/path/to/somewhere/' -e 'pattern'
```

```bash
find . -name "*.ext" -print | xargs grep "something"
```
