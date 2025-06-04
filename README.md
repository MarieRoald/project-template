# Project template

This is a dummy readme for a Python project managed by [PDM](https://pdm-project.org/).
It works with PDM, so if you want to create a new project, then you can simply run

```bash
pdm init https://github.com/marieroald/python-project-template
```

If you don't have PDM installed, then you can follow the [installation instructions](https://pdm-project.org/en/latest/#installation) in the PDM documentation.

## Installation

To install the project, run `pdm install` to install the project and all dependencies in a virtual environment.
Then, run `pre-commit install` to install all pre-commit hooks.
The repo also contains a GitHub actions CI-workflow, which runs the pre-commit hooks and all unit tests on each push and pull request.

## Testing

The repository is set up to use pytest for testing, with the [`pytest-randomly`](https://pypi.org/project/pytest-randomly/) and [`pytest-cov`](https://pypi.org/project/pytest-cov/) plugins for better random number handling in tests and easier coverage measurements.
