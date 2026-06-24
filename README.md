# MapManager Docs

Single-page portfolio site for [mapmanager.net](https://mapmanager.net/), built with MkDocs Material.

## Local development

Requires [uv](https://docs.astral.sh/uv/).

```bash
uv sync
uv run mkdocs serve
```

Open http://127.0.0.1:8000/

## Deploy

Pushes to `main` trigger GitHub Actions, which publishes to the `gh-pages` branch.
