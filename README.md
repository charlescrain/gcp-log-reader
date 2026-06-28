# gcp-log-reader

A small utility for reading Google Cloud Platform logs.

## Development

This repository uses git worktrees. Keep `main` stable and build features in sibling worktrees under `/home/charlescrain/projects/gcp-log-reader/`.

```bash
# main checkout
cd /home/charlescrain/projects/gcp-log-reader/main

# create a feature worktree
git worktree add -b feature/your-feature ../your-feature main
```

## Configuration

Copy `.env.example` to `.env` and fill in local values. Do not commit `.env` files.

```bash
cp .env.example .env
```

Expected environment variables will be refined as the first feature is built.
