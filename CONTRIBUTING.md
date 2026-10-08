# Contributing to CodeLobby

## Workflow

1. Pick or create a focused Issue in the **CodeLobby Development** project.
2. Make sure the Issue is in **Ready** before implementation starts.
3. Create a short-lived branch from `main`.
4. Keep the change focused on the linked Issue.
5. Open a Pull Request into `main`.
6. Request review and address review comments.
7. Merge only after required checks and review pass.

## Branch naming

Use one of these patterns:

- `feat/<issue-number>-short-description`
- `fix/<issue-number>-short-description`
- `chore/<issue-number>-short-description`
- `docs/<issue-number>-short-description`

Example:

`feat/12-create-lobby-endpoint`

## Pull Requests

A Pull Request should:

- link the related Issue
- explain what changed and why
- stay reasonably small
- include or update tests when appropriate
- avoid unrelated formatting or refactoring
- never include credentials or secrets

## Main branch

Do not use `main` for day-to-day development. Changes should reach `main` through reviewed Pull Requests.

## Security

Code submitted by CodeLobby users is untrusted input. Any change related to execution, compilation, containers, filesystem access, networking or resource limits must preserve isolation boundaries and must not run participant code inside the main backend process.
