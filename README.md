# Python Project Template


A simple template for Python projects with boilerplate workflows setup:

- Empty Python app structure
- Basic [pytest](https://docs.pytest.org/) setup
- Makefile (see below for commands)
- [pre-commit](https://pre-commit.com/) configuration
- Static type checking with [mypy](https://mypy.readthedocs.io/en/stable/)
- [GitHub Actions](https://docs.github.com/en/actions) runner for flake8 and pytest
- Pull request template

## Using this template

To get started with this template, simply click the "Use this template" button on GitHub (not fork). For more information on using template repos you can [read the docs](https://docs.github.com/en/repositories/creating-and-managing-repositories/creating-a-repository-from-a-template).


---

# My Project
![](https://img.shields.io/badge/Python-3.9-blue)
[![](https://img.shields.io/badge/Template-Python-yellow)](https://github.com/Iain530/python-project-template)
![](https://github.com/OWNER/REPO/actions/workflows/build.yml/badge.svg?branch=main)
<!-- Replace OWNER and REPO with your new project details above -->

## Developing

After cloning the repo, start by creating a virtual environment, activating it and installing dev requirements:
```bash
# 1. Create virtual environment
python -m venv venv

# 2. Activate virtual environment
source venv/bin/activate  # Linux/Mac
.\venv\Scripts\activate   # Windows

# 3. Install dev requirements
make install-dev
```

## Make Commands

- `make install` - Installs app requirements
- `make install-dev` - Installs app and development requirements
- `make run` - Runs [main.py](./main.py)
- `make test` - Runs unit tests
- `make check-types` - Runs mypy static type checking


---

Created using Iain530's [Python Project Template](https://github.com/Iain530/python-project-template)
