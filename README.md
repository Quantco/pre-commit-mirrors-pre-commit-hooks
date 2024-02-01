# pre-commit-hooks pre-commit hook

pre-commit hook of pre-commit-hooks with conda as a `language` / package manager.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For pre-commit-hooks: see [here](https://github.com/pre-commit/pre-commit-hooks)

## Using pre-commit-hooks with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-pre-commit-hooks
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pretty-format-json-conda # or any other of the hooks in pre-commit-hooks
```
