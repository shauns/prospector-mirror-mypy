prospector mirror mypy
=============

Mirror of prospector package for pre-commit. Includes MyPy support.

For pre-commit: see https://github.com/pre-commit/pre-commit

For prospector: see https://github.com/landscapeio/prospector

Based on: https://github.com/guykisel/prospector-mirror


### Using prospector with pre-commit

Add this to your `.pre-commit-config.yaml`:

    -   repo: git://github.com/shauns/prospector-mirror-mypy
        rev: ''  # Use the sha / tag you want to point at
        hooks:
        -   id: prospector
