---
name: confirm-before-commit-and-push
description: Use whenever work could result in a git commit or push. Requires explicit user confirmation before anything is committed or pushed to the repository.
---

# Confirm Before Commit and Push

## Rules
- Never run `git commit` or `git push` (including amend, force push, or tag pushes) without explicit user confirmation.
- Before asking, show what will be committed or pushed: changed files, the proposed commit message, and the target branch/remote.
- Ask for confirmation separately for the commit and for the push. Approval of one is not approval of the other.
- Confirmation applies only to the specific action shown; ask again for later commits or pushes.
- If the user has not clearly said yes, do not proceed. Silence or ambiguity is not consent.
- Staging or leaving changes uncommitted in the working tree is fine; just do not commit or push them.
