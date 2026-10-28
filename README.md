# CI/CD Final Project

[![License](https://img.shields.io/badge/License-Apache%202.0-blue.svg)](https://opensource.org/licenses/Apache-2.0)
[![Python 3.9](https://img.shields.io/badge/Python-3.9-blue.svg)](https://www.python.org/downloads/release/python-390/)

This repository contains the final project for the **Continuous Integration and Continuous Delivery (CI/CD)** course as part of the IBM DevOps and Software Engineering Professional Certificate.

## Project Overview

This project demonstrates a full CI/CD pipeline implementation using:
- **GitHub Actions** for continuous integration (linting with `flake8` and unit testing with `nosetests` / `pytest`)
- **Tekton Pipelines & Tasks** for continuous deployment to OpenShift / Kubernetes
- Automated building of container images using `buildah`
- Deployment and validation on an OpenShift cluster

## Features

- RESTful API service implementation
- Automated linting and style enforcement
- Comprehensive test suite and code coverage
- Event-driven CI workflow triggered on pull requests and pushes to `main`
- Tekton pipeline automation including clone, lint, test, build, and deploy steps

## License

Copyright (c) IBM Corporation. All rights reserved.

Licensed under the [Apache License, Version 2.0](LICENSE).
