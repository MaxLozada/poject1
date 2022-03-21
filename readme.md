# Project1

[![Production Workflow](https://github.com/MaxLozada/poject1/actions/workflows/prod.yml/badge.svg)](https://github.com/MaxLozada/poject1/actions/workflows/prod.yml)

* [Production Deployment](https://mrlprod.herokuapp.com/)


[![Development Workflow](https://github.com/MaxLozada/poject1/actions/workflows/test-build-deploy.yml/badge.svg)](https://github.com/MaxLozada/poject1/actions/workflows/test-build-deploy.yml)

* [Developmental Deployment](https://mrldev.herokuapp.com/)

Finalizing functions and looks.

Running Locally
To Build with docker compose: docker compose up --build
To run tests, Lint, and Coverage report use this command: pytest --pylint --cov
.pylintrc is the config for pylint, .coveragerc is the config for coverage and setup.py is a config file for pytest
