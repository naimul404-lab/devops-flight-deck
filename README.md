# DevOps Flight Deck

DevOps Flight Deck is an educational project for Git, GitHub, Docker, and CI/CD workflows.

## Overview

This project demonstrates:
- Branching and pull requests
- Merge conflict resolution
- Docker basics
- CI checks with GitHub Actions
- Deployment pipeline concepts

## Run locally

```bash
python3 -m http.server 8000
```

Then open http://localhost:8000.

## Docker

```bash
docker build -t devops-flight-deck .
docker run -p 8000:8000 devops-flight-deck
```

## GitHub Actions

The workflow runs on every push and pull request to validate the project.
