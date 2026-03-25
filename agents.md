# Agent Notes

## After any code changes

Always run `cargo fmt -- --check` to verify formatting before committing.

## Commits and pull requests

- Do not use `git commit --amend` + force push on PR branches. Make a new commit instead — it keeps history visible for reviewers.
- This file (`agents.md`) and `.github/copilot-instructions.md` are private to this fork. Never include either file in PR branches targeting upstream repos.
