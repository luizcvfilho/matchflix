# movies-recomendation

## Setup with uv

1. Install `uv`.
2. Use Python 3.12 or newer.
3. Sync the environment with `uv sync --dev`.
4. Copy `.env.example` to `.env` and add your TMDB API key.

## Dependencies

This project uses only `uv` for dependency management.
Dependencies are declared in `pyproject.toml`, and resolved versions are stored in `uv.lock`.

- To add a runtime dependency: `uv add package-name`
- To add a development dependency: `uv add --dev package-name`

## Useful commands

- `uv run ruff check .`
- `uv run ruff format .`
- `uv run pre-commit install`
