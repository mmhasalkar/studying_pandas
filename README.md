# Studying Pandas

Prepared by: _Mukunda M Mhasalkar_

Prepared on: 28th October 2021

## Setting up the environment

---

### Creating the virtual environment

```
virtualenv venv -p python3
```

### Activate the virtual environment

```
source venv/bin/activate
```

You'll might need to install the `ipython` before moving to the next step using command below:

```
pip install ipython
```

### Make the virtual environment python executable available in jupyter-notebook

```
ipython kernel install --user --name=<name_the_env>
```

### Install Pandas & Matplotlib

```
pip install pandas matplotlib
```

### Install Jupyter-Notbook if not installed already

```
sudo apt-get install jupyter-notebook
```

## Running the notebook

---

### Starting jupyter-notebook

```
jupyter-notebook
```

You'll see the browser window opened in which the current directory is opened. Click on the `pandas_basics.ipynb` to open the Notebook.

You can select the kernel to run the notebook in the environment we've created by selecting `Kernel > Change kernel > <name_the_env>`.

Here, in above step, you need to select the kernel with the name we've added in the jupyter-notebook in one of the above steps. This is required to isolate the environment and dependencies of this project tutorial with other Python interpreters.

Your Studying Pandas notebook is now ready to use and you can start studying the code now.

Happy Learning!
