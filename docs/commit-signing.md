# Commit signing policy

## GitHub

Cursor Cloud Agent commits are signed with Cursor-managed **SSH** (Ed25519 / HSM).
GitHub should show these as **Verified**. Personal OpenPGP (GPG) is not used for Agent commits.

## Gitea

Agent / bot commits may be unsigned or unverified. That is accepted for this workflow.
Local commits signed with the owner's GPG key remain verified as before.
