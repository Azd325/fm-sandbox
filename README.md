# fm-sandbox

Scratch repository for live checks that need a real GitHub pull request.

- Each check opens a draft PR from a scratch branch.
- After the check, the PR is closed without merging and the branch is deleted.
- Nothing is ever merged to `main`.
- `main` declares no CI (`.no-mistakes.yaml`). A check that needs CI adds its own workflow on its scratch branch.
