# Git Workflow & Branch Protection

To ensure code quality and team synchronization, we have implemented the following rules for the main branch:

## Main Branch Protection Rules

- No Direct Commits: All changes must be submitted via Pull Requests.
- Mandatory Peer Review: At least one team member must approve a Pull Request before it can be merged.
- Stale Approval Dismissal: Approvals are automatically reset when new commits are pushed to a PR to ensure the final version is always reviewed.
- Conversation Resolution: All comments and discussions in a PR must be resolved before merging.
- History Integrity: Force pushes and branch deletions are strictly prohibited to maintain a clear audit trail of all contributions.

## How to Contribute

- Create a feature branch from dev (e.g., feat/feature-name).
- Commit your changes with clear, meaningful messages.
- Open a Pull Request against the develop branch.
- Wait for a Peer Review and resolve any requested changes.
- Once approved and tested, the code will be merged.

## Other rules

- A refactor that changes behavior is not a refactor — it’s a feature or a bug.
- If a feature changes behavior, documentation must change too.
