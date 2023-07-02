# delete node_modules from all sub folders within parent folder

## replace path with path to parent folder

```
find /path/to/parent -name "node_modules" -type d -prune -exec rm -rf {} +
```
### example:
```
find Desktop/Projects/ -name "node_modules" -type d -prune -exec rm -rf {} +
