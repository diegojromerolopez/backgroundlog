# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## v0.2.5

### Fixes

- Remove dead code.
- Improve the performance tests.

## v0.2.4

### Fixes
- New parameters in ThreadHandler:
  - flush_interval: maximum time allowed for the pending error log records to be read.
  - shutdown_timeout: maximum time allowed for thread to join.
- Increase test coverage.
- Format code to black with single quotes, flake8 and isort. 

## v0.2.3

### Fixes

- Fix the unit of the time measurements in the README.

## v0.2.2

### Fixes

- Show the mean and the std deviation for the time measurements.

## v0.2.1

### Fixes

- Fix the project information in the pyproject.toml.

## v0.2.0

### Features

- Renaming some parts of the project that had a typo.

## v0.1.1

### Fixes

- Automatic deployments to pypi.

## v0.1.0

- First release