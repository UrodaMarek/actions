# Clean Workspace

Cleans the current workspace prior to running the checkout action, to ensure the job starts with a clean slate.

```yaml
- uses: Cryptomines-Network/actions/clean-workspace@main

- name: Checkout Code
  uses: actions/checkout@v2
```
