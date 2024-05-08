# python-workflows
GitHub Action Python workflows

| Name                 | Description                      |
|----------------------|----------------------------------|
| [gh-pages-publish.yml](https://github.com/JeffersonLab/python-workflows/blob/main/.github/workflows/gh-pages-publish.yml) | Publish API docs to GitHub Pages |
| [gh-release.yml](https://github.com/JeffersonLab/python-workflows/blob/main/.github/workflows/gh-release.yml) | Create a GitHub Release |
| [pypi-publish.yml](https://github.com/JeffersonLab/python-workflows/blob/main/.github/workflows/pypi-publish.yml) | Publish an artifact on PyPi |
| [unit-ci.yml](https://github.com/JeffersonLab/python-workflows/blob/main/.github/workflows/unit-ci.yml) | Build and run Unit tests |

## Workflow Updates
Workflows are versioned in semver just as with regular software, however, the GitHub Action workflows convention is to reference a major version number such that backwards compatible minor and patch updates are received automatically.  This means a separate major tag such as `v1` must be moved after each release.  To move a major tag after a release execute (`v1` shown):

```
git tag -f v1
git push --tags -f
```

## See Also
- [Other workflows](https://github.com/search?q=org%3Ajeffersonlab+topic%3Agh-action-workflow&type=repositories)
- [Projects using this](https://github.com/search?q=org%3Ajeffersonlab+topic%3Apython-workflows&type=repositories)
