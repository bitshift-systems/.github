# .github

Shared settings and actions for Bitshift. Everything here applies to every repo
in the organisation, either because GitHub reads it from this repository by name
or because the other repositories pull it in explicitly.

## Composite actions

Shared CI steps, each versioned and tagged on its own. Reference them by commit
SHA; a branch or tag reference trips workflow linting audit rules in calling
repositories.

| Action                                     | Purpose                                                  |
| ------------------------------------------ | -------------------------------------------------------- |
| [`setup-repo`](./actions/setup-repo)       | Sets up Mise with toolchain-specific caches.             |
| [`workflow-lint`](./actions/workflow-lint) | Lints workflows and action definitions with jactionlint. |

Each has its own README, changelog and `<component>-<version>` tag, so one
action's release never moves the other's version.

## Community health files

Various Markdown files in this repository are served by GitHub to any repo in
the org that does not provide its own. A repository-level file always wins.
