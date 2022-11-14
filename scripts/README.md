# Tools

1. [Version validation](#version-validation)

# Version validation

## Description
`version-validation.sh` is a shell script validating a version format.

## Usage

### Terminal

- Open a terminal

- Enter:
```
sh version-validation.sh {x.y.z}
```

### Bitrise

- Open https://app.bitrise.io/app/8ffb80da1f097aa5

- Click on `Start/schedule build`

- Click on `Advanced` tab

- Select `version-validation` in `Workflow, Pipeline` section

- Add TEST_VERSION and a value(example: 3.2.1) in `Custom Environment Variables` section

- Click on `Add Environment Variable`

- Click on `Start Build`

## Example
- Command line:
```
sh version-validation.sh 10.0.0
```

- Result:
```
version input is valid
```
