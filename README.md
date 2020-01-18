# install-azcopy-action

<a href="https://github.com/kheiakiyama/install-azcopy-action/actions"><img alt="install-azcopy-action status" src="https://github.com/kheiakiyama/install-azcopy-action/workflows/build-test/badge.svg"></a>

# Usage

```
steps:
- uses: actions/checkout@v2
- uses: kheiakiyama/install-azcopy@v1
- run: azcopy --source {SOURCE} --destination {DEST} --dest-key $STORAGE_KEY --recursive --set-content-type
```

# Develop

See [develop-references.yml](develop-references.yml)