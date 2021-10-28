# Learning Pandas

## Creating the virtual environment

```
virtualenv venv -p python3
```

## Activate the virtual environment

```
source venv/bin/activate
```

## Make the virtual environment python executable available in jupyter-notebook

```
ipython kernel install --user --name=<name_the_env>
```

You'll might need to install the `ipython` using command below:

```
pip install ipython
```