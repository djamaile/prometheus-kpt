# prometheus

## Description
sample description

## Usage

### Fetch the package
`kpt pkg get REPO_URI[.git]/PKG_PATH[@VERSION] prometheus`
Details: https://kpt.dev/reference/cli/pkg/get/

### View package content
`kpt pkg tree prometheus`
Details: https://kpt.dev/reference/cli/pkg/tree/

### Apply the package
```
kpt live init prometheus
kpt live apply prometheus --reconcile-timeout=2m --output=table
```
Details: https://kpt.dev/reference/cli/live/
