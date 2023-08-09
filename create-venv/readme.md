# Create venv

Creates a venv in the runner temporary path that will be removed upon completion of the job.
This can be used in combination with the `activate-venv` action such as shown below.

```yaml
- uses: UrodaMarek/actions/create-venv@main
  id: create-venv

- uses: UrodaMarek/actions/activate-venv@main
  with:
    directories: ${{ steps.create-venv.outputs.activate-venv-directories }}
```
