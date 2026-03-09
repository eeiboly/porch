# my-package

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] my-package`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree my-package`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init my-package
kpt live apply my-package --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
