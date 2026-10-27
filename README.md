# RepoPilot

RepoPilot is an AI-powered software engineering agent designed to help
developers understand, modify, test, and improve existing repositories
through a controlled, reviewable workflow.

## Principles

- Correctness and security over speed.
- Small, reviewable changes.
- Deterministic validation and reproducible results.
- Explicit approval before applying code changes.
- Automated testing and auditable execution history.

## Planned technology stack

- Frontend: Next.js, React, TypeScript, and Tailwind CSS.
- Backend: Python, FastAPI, Pydantic, and SQLAlchemy.
- Database: PostgreSQL with Alembic migrations.
- Tooling: Git, GitHub, pnpm, Docker, and uv.

## Project status

Phase 0: Clean repository setup and development foundation.

Application features have not yet been implemented.

## Development

See [docs/development.md](docs/development.md) for project setup
progress, decisions, verification results, and the next milestone.

## Security

Never commit credentials, API keys, database passwords, or private
repository data. AI-generated code must not be executed without
appropriate isolation and explicit controls.
