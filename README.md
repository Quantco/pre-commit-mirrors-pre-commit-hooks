# pre-commit-hooks mirror

Mirror of pre-commit-hooks for pre-commit with conda as a language.

For pre-commit: see [here](https://github.com/pre-commit/pre-commit)

For pre-commit-hooks: see [here](https://github.com/pre-commit/pre-commit-hooks)

## Using pre-commit-hooks with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/quantco/pre-commit-mirrors-pre-commit-hooks
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pre-commit-hooks-conda
```
