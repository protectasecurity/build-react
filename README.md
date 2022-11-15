# Build ReactJS GitHub Actions

Build ReactJS GitHub Actions allows you to build ReactJS projects

## Example usage

```yaml
on: [push]

jobs:
  build:
    runs-on: ubuntu-latest
    steps:
      - uses: protectasecurity/build-react@v1
```
Output Artifact: dist


## Inputs

- `node-version` **Optional** Node JS version to use
- `workspace` **Optional** Relative path under $GITHUB_WORKSPACE to place the project

## Authors

- [Ronnie Ayala](https://github.com/ronnieacs)