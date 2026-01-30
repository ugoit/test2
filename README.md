# myapp

## Goal
Template repo for fast-start Python projects with CI + auto-merge.

## Requirements
- Python 3.12
- uv (recommended)

## Setup (dev)
```bash
uv venv
uv pip install -e ".[dev]"
```

## Run
```bash
python -m myapp
```

## Test / Lint
```bash
ruff format --check .
ruff check .
pytest
```

test
