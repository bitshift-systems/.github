# setup-repo

Installs Mise & toolchains, ensuring caches are used for supported languages.

## Usage

The action uses the local Mise configuration, so the repository must be checked out first.

```
jobs:
  rust-build:
    name: Rust Build
    runs-on: ubuntu-26.04
    permissions:
      contents: read
    steps:
      - name: Checkout
        uses: actions/checkout@<sha> # v7.0.1
        with:
          persist-credentials: false

      - name: Setup repo
        uses: bitshift-systems/.github/actions/setup-repo@<sha> # setup-repo-1.0.0
        with:
          cache-key: rust-build
```

Reference it by commit SHA.

## Inputs

| Input       | Default   | Description                                           |
| ----------- | --------- | ----------------------------------------------------- |
| `cache`     | `true`    | Whether or not to enable caching for this run         |
| `cache-key` | `default` | Shared cache key for all caches opened by this action |
