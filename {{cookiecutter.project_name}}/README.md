# {{cookiecutter.project_name}}

[![Build status](https://img.shields.io/github/actions/workflow/status/{{cookiecutter.author_github_handle}}/{{cookiecutter.project_name}}/main.yml?branch=main)](https://github.com/{{cookiecutter.author_github_handle}}/{{cookiecutter.project_name}}/actions/workflows/main.yml?query=branch%3Amain)

{{cookiecutter.project_description}}

## Getting started

### 1. Clone

First, create a repository on GitHub with the same name as this project, and then run the following commands:

```bash
git clone git@github.com:{{cookiecutter.author_github_handle}}/{{cookiecutter.project_name}}.git
```

### 2. Set Up Your Development Environment

Then, install the environment and the pre-commit hooks with

```bash
uv sync
uv run pre-commit install
```

This will also generate your `uv.lock` file

## Releasing a new version

TODO
