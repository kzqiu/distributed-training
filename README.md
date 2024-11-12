# distributed-training

## Development Setup
Create a virtual environment with Python 3.10+ and install dependencies from dev-requirements.txt.

```bash
> python -m venv .venv
> source .venv/bin/activate
> pip install -r dev-requirements.txt
```

Then, install pre-commit hooks to lint and format code locally:

```bash
> pre-commit install
pre-commit installed at .git/hooks/pre-commit
```
