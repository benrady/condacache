
# CondaCache

An alternative to `conda env create` that caches environments that have already been installed

```
Usage:

  $ condacache <environment file> <venv directory>
```

## Configuration

By default, condacache will write to a cache directory named `.condacache` as a peer of your venv directory. You can configure this by setting the `CONDACACHE_DIR` environment variable

