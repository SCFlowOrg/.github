# Contributing to SCFlow

Thank you for helping. This guide applies to every repository of the organization unless the repository has its own.

## Before you start

- Search the existing issues first; add to one if it already covers your case.
- For a bug or task, open an issue in the repository of the component concerned. Use the issue forms provided.
- For work that spans several repositories, the work is tracked by a parent issue with one sub-issue per affected repository. Link them as sub-issues and reference them as `SCFlowOrg/<repo>#<number>`.

## Issues

- Write titles that are short, imperative and in English.
- One topic per issue.
- Never include secrets, credentials or private data.

## Labels

Every repository uses the same set, in addition to the GitHub default labels.

| Label | Meaning |
| --- | --- |
| `area:model` | Data and model of `scflow-core` |
| `area:graph` | Graph views and layout |
| `area:map` | Map views |
| `area:ai` | AI assistants and skills |
| `area:plugin-api` | Plugin contracts and builder |
| `area:desktop` | Tauri desktop app and installers |
| `area:i18n` | Translations |
| `area:docs` | Documentation |
| `sync` | Copy of packages or shell between repositories |
| `cross-repo` | Linked to issues in other repositories |
| `blocked` | Waiting on another issue or a decision |

## Pull requests

- Keep each pull request focused and small enough to review.
- Link the issue it closes with `Fixes SCFlowOrg/<repo>#<number>`.
- Run the checks of the repository (typecheck and tests) before asking for review.
- Update the documentation in the same pull request as the code.

## History

Some repositories are synchronized with an external editor. On those repositories, never rewrite published history: no force push, and no rebase, amend or squash of commits that are already pushed. Keep the default branch in a working state.

## Language

Code, identifiers, comments and documentation are written in English.
