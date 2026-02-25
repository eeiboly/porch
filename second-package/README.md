# second-package

## Description
Another KPT Package

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] second-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree second-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init second-package
kpt live apply second-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
