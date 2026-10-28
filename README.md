# ci-templates-2

Central reusable GitHub Actions workflows.

Usage from an app repo:

```yaml
jobs:
  ci:
    uses: Imsprk/ci-templates-2/.github/workflows/reusable-ci.yml@v1
    with:
      app-name: my-app
    secrets: inherit
```
