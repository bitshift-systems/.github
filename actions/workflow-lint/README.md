# workflow-lint

Lints workflows and action definitions with [jactionlint](https://jactionlint.jdx.dev/).

## Usage

> [!IMPORTANT]
> Before calling this action, check out the repository that you want to lint.
> Declare `jactionlint` and `shellcheck` in that repository's Mise configuration, such as `mise.toml` or `.mise/config.toml`.
> The action uses the calling repository's tool versions. It does not load the Mise configuration from `bitshift-systems/.github`.
> To quickly add both tools, run `mise use --pin jactionlint@latest shellcheck@latest`.

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
