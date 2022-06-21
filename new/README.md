# new

## Description
new

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] new`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree new`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init new
kpt live apply new --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
