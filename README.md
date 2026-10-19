# greet-ci

Greeting program with GitHub Actions CI.

## Install

```bash
uv sync --locked
```

## Run

```bash
uv run --locked python greet.py Hee   # Hello, Hee!
uv run --locked python greet.py       # Hello, world!
```

## Check

```bash
uv run --locked pytest -q greet.py
uv run --locked black --check greet.py
uv run --locked flake8 greet.py
uv run --locked mypy greet.py
uv build
```
