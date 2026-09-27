# Nexus Artifact Management Lab

A DevOps portfolio project demonstrating artifact repository management and CI/CD integration with Nexus Repository.

## What this demonstrates

- Maven artifact publishing and retrieval
- Nexus repository concepts and repository separation
- Jenkins-to-Nexus delivery flow
- Versioned build artifacts
- Artifact promotion between environments
- Repository health and retention concepts
- GitHub Actions validation

## Architecture

Developer -> Git -> Jenkins Build/Test -> Nexus Repository -> Deployment Pipeline -> Environment

See docs/architecture.md and docs/architecture.svg.

## Repository model

Use separate hosted repositories for release and snapshot artifacts. Configure proxy repositories where external dependency caching is required, and group repositories to provide a single consumption endpoint.

## Production hardening

Use TLS, least-privilege service accounts, secret management, retention policies, repository cleanup tasks, backup/restore procedures and audit logging.

## Interview topics

- Why artifacts should be immutable
- Hosted vs proxy vs group repositories
- Snapshot versus release lifecycle
- Nexus authentication from Jenkins
- Artifact promotion and rollback

## Skills

Nexus Repository, Jenkins, Maven, CI/CD, artifact management, Git, security and release engineering.
