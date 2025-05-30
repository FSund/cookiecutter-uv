# Cookiecutter

This is a modern Cookiecutter template that can be used to initiate a Python project with all the necessary tools for development, testing, and deployment. It supports the following features:

- [uv](https://docs.astral.sh/uv/) for dependency management
- CI/CD with [GitHub Actions](https://github.com/features/actions)
- Pre-commit hooks with [pre-commit](https://pre-commit.com/)
- Code quality with [ruff](https://github.com/charliermarsh/ruff), [mypy](https://mypy.readthedocs.io/en/stable/) and [deptry](https://github.com/fpgmaas/deptry/)
- Testing with [pytest](https://docs.pytest.org/en/7.1.x/)
- Containerization with [Docker](https://www.docker.com/) or [Podman](https://podman.io/)

## Quickstart

On your local machine, navigate to the directory in which you want to
create a project directory, and run the following command:

```bash
uvx cookiecutter https://github.com/fsund/cookiecutter-uv.git
```

or if you don't have `uv` installed yet:

```bash
pip install cookiecutter
cookiecutter https://github.com/fsund/cookiecutter-uv.git
```

Follow the prompts to configure your project. Once completed, a new directory containing your project will be created. Then navigate into your newly created project directory and follow the instructions in the `README.md` to complete the setup of your project.

## Acknowledgements

This project is partially based on [cookiecutter-pypackage](https://github.com/audreyfeldroy/cookiecutter-pypackage)
repository and the [cookiecutter-uv](https://github.com/fpgmaas/cookiecutter-uv) repository.
