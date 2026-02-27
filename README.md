# air-pre-commit

A [pre-commit](https://pre-commit.com/) hook for [Air](https://github.com/posit-dev/air).

### Using Air with pre-commit

To run Air via pre-commit, add the following to your `.pre-commit-config.yaml`:

```yaml
repos:
- repo: https://github.com/posit-dev/air-pre-commit
  # Air version
  rev: 0.8.2
  hooks:
    # Run the formatter
    - id: air-format
```

## Acknowledgements

air-pre-commit is a fork of [astral-sh/ruff-pre-commit](https://github.com/astral-sh/ruff-pre-commit).
