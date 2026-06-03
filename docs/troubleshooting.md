# Troubleshooting

## GitHub CLI is not logged in

Run:

```bash
gh auth login
```

Then verify:

```bash
gh auth status
```

## The script says the working tree is dirty

Commit or stash your changes before running the playground.

Check status:

```bash
git status
```

## The PR cannot be merged

Common causes:

- Branch protection requires reviews.
- The repository is archived.
- You do not have write access.
- The branch has conflicts.

Use your own fork or a repository where you have full write access.

## Badge did not appear

GitHub achievements can take time to process.

Check:

- The repository is public.
- The PR was merged, not closed.
- The issue was closed within five minutes for Quickdraw.
- The co-author email matches a GitHub account for Pair Extraordinaire.
- Achievements are visible in your profile settings.

## Actions workflow did not unlock anything

The Actions workflow is a demo. Achievement credit is more reliable when the local script runs under your authenticated GitHub account.
