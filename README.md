
# CondaCache

An alternative to `conda env create` that caches environments that have already been installed

```
Usage:

  $ condacache <environment file> <venv directory>
```

## Configuration

CondaCache can be configured with the following environment variables:

```
  CONDACACHE_REPO_URL - HTTP PUT compatible service for storing tarballs
    ex: 'https://artifactory.example.com/artifactory/condacache'

  CONDACACHE_AUTH (optional) - HTTP header used for auth when uploading to the REPO URL
    ex: 'Authorization: Bearer <token>'"
```
