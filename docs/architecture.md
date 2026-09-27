# Nexus Architecture

## Flow

Git source -> Jenkins build and test -> Maven package -> Nexus hosted repository -> deployment pipeline.

## Repository types

- Hosted: stores organization-owned artifacts.
- Proxy: caches artifacts from external repositories.
- Group: exposes a combined consumption endpoint.

## Operational controls

Use immutable release versions, controlled promotion, least-privilege credentials, retention policies, backups and audit logs.
