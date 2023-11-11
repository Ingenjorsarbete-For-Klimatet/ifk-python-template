<h1 align="center">ifk-python-template</h1>

<p align="center">
    <a href="https://www.python.org">
        <img src="https://img.shields.io/badge/Python-3.9%20|%203.10%20|%203.11%20|%203.12-blue" alt="Python: 3.9 - 3.12" style="max-width: 100%;">
    </a>
    <a href="https://pytest.org">
        <img src="https://img.shields.io/badge/Testing_framework-pytest-a04000" alt="Testing framework: pytest" style="max-width: 100%;">
    </a>
    <a href="https://github.com/astral-sh/ruff">
        <img src="https://img.shields.io/endpoint?url=https://raw.githubusercontent.com/astral-sh/ruff/main/assets/badge/v2.json" alt="Linter and formatter: ruff" style="max-width: 100%;">
    </a>
    <a href="http://mypy-lang.org">
        <img src="https://img.shields.io/badge/Type_checker-mypy-1674b1" alt="Type checker: mypy" style="max-width: 100%;">
    </a>
</p>

## Description

Welcome to ifk-python-template.

## Configuration

When you start a new project, apart from the obvious changes,
there are some details to consider.

- Build workflow, follow the guide in [dynamic badges](https://github.com/Schneegans/dynamic-badges-action).
- To build docs, change `branch` in `github/workflows/github-action-docs.yaml`
from `["SET_TO_MAIN"]` to `["main"]`. You also need to activate Pages under repo
Settings/Pages.

Install `copier` (install `pipx` through `pip`) as

```bash
pipx install copier
```

and then do

```bash
copier copy https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template.git /path/to/project-name
```

Copier supports updating projects based on templates when the template updates.
See <a href="https://copier.readthedocs.io/en/stable/" taget="_blank">copier docs</a>.
