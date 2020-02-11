# OQP

OQP is a ridiculously small tool for working with Jupyter notebooks and [DVC](https://dvc.org).

## Notebook to Python script

Convert a notebook to a Python script:

```shell
oqp script -i path/to/notebook.ipynb
```

Generate a DVC run command for a Python script:

```shell
oqp dvc -i path/to/script.py
```

`oqp` writes its result on stdout.
