# python-notebook-template

A template project for Python / Jupyter projects using Poetry.

## Setup

This project uses Poetry to manage dependencies and python virtual environments. After cloning this repository, be sure [Poetry is installed](https://python-poetry.org/) then run:

```
poetry install
```

To add dependecies:

```
poetry add foobar
```

Update `.env` with any relevant environment variables, then to start Jupyter:

```
poetry shell
jupyter notebook
```
