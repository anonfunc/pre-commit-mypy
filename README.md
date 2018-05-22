mypy mirror
===========

Mirror of mypy package for pre-commit

For pre-commit: see https://github.com/pre-commit/pre-commit

For mypy: see http://mypy.readthedocs.io/en/latest/index.html


### Using mypy with pre-commit

Add this to your `.pre-commit-config.yaml`:

    - repo: https://github.com/anonfunc/pre-commit-mypy
      rev: master
      hooks:
      - id: mypy
