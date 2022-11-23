<h1 align="center">ifk-python-template</h1>

<p align="center">
    <a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-build.yaml">
        <img src="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-build.yaml/badge.svg?branch=main" alt="build" style="max-width: 100%;">
    </a>
    <a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-build.yaml">
        <img src="https://img.shields.io/endpoint?logo=github&labelColor=%23333a41&logoColor=%23959da5&url=https://gist.githubusercontent.com/mgcth/955d89d05ed9ca61fb3774bc68bbae33/raw/ifk-python-template-coverage-badge.json" alt="coverage" style="max-width: 100%;">
    </a>
    <a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-docs.yaml">
        <img src="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-docs.yaml/badge.svg?branch=main" alt="docs" style="max-width: 100%;">
    </a>
    <a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-lint.yaml">
        <img src="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-lint.yaml/badge.svg?branch=main" alt="lint" style="max-width: 100%;">
    </a>
    <a href="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-type.yaml">
        <img src="https://github.com/Ingenjorsarbete-For-Klimatet/ifk-python-template/actions/workflows/github-action-type.yaml/badge.svg?branch=main" alt="type" style="max-width: 100%;">
    </a>
</p>

<p align="center">
    <a href="https://www.python.org">
        <img src="https://img.shields.io/badge/Python-3.9%20|%203.10-blue" alt="Python: 3.9 | 3.10" style="max-width: 100%;">
    </a>
    <a href="https://pytest.org">
        <img src="https://img.shields.io/badge/Testing_framework-pytest-a04000" alt="Testing framework: pytest" style="max-width: 100%;">
    </a>
    <a href="hhttps://flake8.pycqa.org">
        <img src="https://img.shields.io/badge/Linter-flake8-ff69b4" alt="Linter: flake8" style="max-width: 100%;">
    </a>
    <a href="http://mypy-lang.org">
        <img src="https://img.shields.io/badge/Type_checker-mypy-1674b1" alt="Type checker: mypy" style="max-width: 100%;">
    </a>
    <a href="https://github.com/PyCQA/bandit">
        <img src="https://img.shields.io/badge/Security-bandit-yellow.svg" alt="Security: bandit" style="max-width: 100%;">
    </a>
    <a href="https://github.com/psf/black">
        <img src="https://img.shields.io/badge/Code_style-black-black" alt="Code style: black" style="max-width: 100%;">
    </a>
</p>

## Description

IFK python template for future python projects.

## Configuration

When you start a new project, apart from the obvious changes,
there are some details to consider.

- Build workflow, follow the guide in [dynamic badges](https://github.com/Schneegans/dynamic-badges-action).
- To build docs, change `branch` in `github/workflows/github-action-docs.yaml`
from `["SET_TO_MAIN"]` to `["main"]`. You also need to activate Pages under repo
Settings/Pages.
