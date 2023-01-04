# pre-commit-hooks

[Pre commit](https://pre-commit.com/) hooks for twisto purposes. Starting with poetry checks.

### Example usage
Add this to `.pre-commit-config.yaml` under `repos:`. 
Change the revision (`rev`) tu current version.

    -   repo: https://github.com/TwistoPayments/pre-commit-hooks
        rev: v1.0
        hooks:
            -   id: poetry-check
            -   id: poetry-lock-check
