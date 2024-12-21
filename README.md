# yamllint
Github Actions for "Yamllint" for a specific PR


## Agenda

This action is helpful to add it as a linter to your repo which needs to execute yaml linter only to the specific files that was modified in your PR rather than checking the netire repository files.
## To whom it is useful

if you need to execute yaml linter only to the specific files that was modified in your PR rather than checking the netire repository files

## Pre-requisites

1. You can directly start using it.


## How to works?

An action has been created to add an yaml linter only to the specific files that was modified in your PR. It has all the dependancies installed, all you have to do is use this and create a yamlinter.yaml in your repo.

like : https://github.com/arun291091/yamllint/blob/main/.github/workflows/sampleyamllinter.yaml 


## How to use?

Use this action within your GitHub workflow step where you need to wait for some additional approval before proceeding to the next step.

```
      - name: Yaml Linter GHA Action
        uses: arun291091/yamllinter@v1
``` 


## How to report issues?

Raise an issue via github for any issues.
