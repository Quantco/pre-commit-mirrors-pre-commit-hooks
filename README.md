pre-commit-hooks(-conda) mirror
===============================

Mirror of pre-commit-hooks with conda as a language.

For pre-commit: see https://github.com/pre-commit/pre-commit
For pre-commit-hooks: see https://github.com/pre-commit/pre-commit-hooks

### Using pre-commit-hooks with pre-commit and conda:

Add this to your `.pre-commit-config.yaml`

```yaml
 - repo: https://github.com/Quantco/pre-commit-mirrors-pre-commit-hooks
   rev: ''  # Use the sha / tag you want to point at
   hooks:
     - id: pretty-format-json-conda  # or any other of the hooks in pre-commit-hooks
```
