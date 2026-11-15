# DevOps Flight Deck

DevOps Flight Deck is an educational project for Git, GitHub, Docker, and CI/CD workflows.

## Goal

This project turns DevOps concepts into a simple visual dashboard that helps learners understand:

- Git branching strategies
- Pull requests and code review
- Merge conflict resolution
- Docker and container basics
- GitHub Actions CI pipeline
- Deployment workflow concepts

## Project structure

```text
.
├── .github/
│   └── workflows/
│       └── ci.yml
├── index.html
├── style.css
├── script.js
├── server.py
├── Dockerfile
├── docker-compose.yml
├── README.md
├── .gitignore
└── .gitignore
```

## Run locally

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

## Run via Docker

```bash
docker compose up --build
```

Then open:

```text
http://localhost:8000
```

## GitHub Actions CI

The workflow validates the Python app on every push and pull request.

## Learning outcomes

- Understand how branches protect the main codebase
- Learn how pull requests improve review quality
- Handle merge conflicts without losing work
- Use Docker to standardize environments
- See how CI/CD automates validation and deployment
