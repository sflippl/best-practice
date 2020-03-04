# Jupyter Lab

## Installation

```
conda install jupyterlab
```

## Add Python files

```
jupyter labextension install jupyterlab-python-file
```

## Add vertical ruler in files

Add the following snippet to the advanced settings editor -> Text editor:

```
{
    "editorConfig": {
        "rulers": [80]
    }
}
```

Add the following snippet to the advanced settings editor -> Notebook:

```
{
    "codeCellConfig": {
        "rulers": [80]
    }
}
```
