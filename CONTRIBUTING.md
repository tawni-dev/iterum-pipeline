# Contributing

This repository is the supply chain authority for Iterum projects.

## Rules

- No PR may modify `canon.json` without explicit owner approval via CODEOWNERS.
- Under the documented non-admin trust model, agents may not merge changes to this repository.
- All SHA, version, and digest values must be verified by the human maintainer against the GitHub API or official release pages before a PR is approved.
- Do not open PRs to update canon.json from automated tooling without human verification of each changed value.

## Updating canon.json

Open a PR with the proposed changes. In the PR description, include:
- Which values changed and why
- The command used to verify each new SHA or version
- A confirmation that `npm audit` passes for any changed dependency versions

The maintainer reviews and approves. No merge without approval.
