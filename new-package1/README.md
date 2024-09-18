# new-package1

## Description
sample description

second edit (one more.....). Some thing extra

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] new-package1`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree new-package1` to view
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package with new changes
```
kpt live init new-package1
kpt live apply new-package1 --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
