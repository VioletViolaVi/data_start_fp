# Data start

This repository contains initial setup, installation, and organisation for introducing data analysis/science concepts.

## Installation

1. Activate the Pipfile environment

```bash
pipenv shell
```

2. Install all required packages

```bash
pipenv install
```

3. Install a useful extension (allows Jupyter to display certain types of visualisation)

```bash
jupyter labextension install jupyterlab-plotly
```

4. Make Jupyter aware of the environment

```bash
python -m ipykernel install --user --name=`basename $VIRTUAL_ENV`
```

## Development

Ensure that you are in the appropriate environment (`pipenv shell`). Then,

```bash
jupyter-lab
```

You may need to skip the hyphen.

```bash
jupyter lab
```

Once the server has loaded, create a new notebook using the environment kernel.