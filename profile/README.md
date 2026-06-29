# pipewell

Open-source data engineering tools built with Python.

## Projects

| Project | Description | Install |
|---|---|---|
| [jira-ingest](https://github.com/pipewell/jira-ingest) | Async Jira Cloud pipeline: fetches projects, boards, issues and transitions into any SQLAlchemy-compatible database | `pip install pipewell-jira-ingest` |
| [confluence-publisher](https://github.com/pipewell/confluence-publisher) | GitHub Action that publishes Markdown docs from your repo to Confluence Cloud or Data Center | [Marketplace](#) |

## Design principles

- **Zero lock-in**: SQLAlchemy-backed loaders support PostgreSQL, Redshift, SQLite, and more
- **Async-first**: built on `asyncio` + `aiohttp` for high-throughput ingestion
- **CI-friendly**: thin GitHub Actions wrappers, no server required
- **Tested**: every release ships with a full pytest suite and mypy strict type-checking
