# Makefile demo

A [demo project](https://calmcode.io/course/makefiles/the-problem) from calmcode

Created with Python 3.12.6.

In this project there is a single simple function in `common.py`.

Commonly run tasks during development are

- Linting, provided by `flake8`
- Unit testing, by `pytest`
- Generating HTML docs, by `pdoc3`

The `Makefile` wraps up these commonly run tasks for convenience, so that you can e.g. `make check` to run linting, tests, and docs in one fell swoop.

## Use

### Set up a virtual environment

```shell
python -m venv .venv
source .venv/bin/activate
```

### Install dev requirements

```shell
make dev
```

### Available rules

For a full list of rules in the `Makefile` and their outcomes

```shell
make help
```
