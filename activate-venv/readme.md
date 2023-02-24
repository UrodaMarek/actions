# Activate virtual environment

Provides cross-platform activation of a Python virtual environment.
By default it searches in `venv/` then `.venv/`.
This is configurable via a JSON list passed to the `directories` parameter.

```yaml
- uses: serwisgalena/actions/activate-venv@main
```

```yaml
- uses: serwisgalena/actions/activate-venv@main
  directories: '["another_virtualenv/"]'
```
