# workflow-lint

Lints workflows and action definitions with [jactionlint](https://jactionlint.jdx.dev/).

## Usage

The action lints the working directory, so the repository must be checked out first.

```
jobs:
  workflow-lint:
    name: Workflow Lint
    runs-on: ubuntu-26.04
    permissions:
      contents: read
    steps:
      - name: Checkout
        uses: actions/checkout@<sha> # v7.0.1
        with:
          persist-credentials: false

      - name: Lint workflows
        uses: bitshift-systems/.github/actions/workflow-lint@<sha> # workflow-lint-1.0.0
```

Reference it by commit SHA.

## Inputs

| Input                 | Default  | Description                   |
| --------------------- | -------- | ----------------------------- |
| `jactionlint-version` | `latest` | Version of jactionlint to run |
