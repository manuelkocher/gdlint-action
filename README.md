# gdlint action

This action runs `gdlint`, a GDScript linter, on a defined directory inside the github repository. This action uses `gdtoolkit` to run `gdlint`.

## Inputs
### python_version
Specify the python version used to install `gdtoolkit`. Defaults to version 3.10.

### gdtoolkit_version
`gdtoolkit` version that should be used to run `gdlint`. Defaults to the newest version.

### directory
Directory on which `gdlint` should be run. Defaults to the root directory of the repository.

## Outputs
The action fails if gdlint detects any issues, otherwise it will return a success.
