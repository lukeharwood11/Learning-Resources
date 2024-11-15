# 01-MNIST

This folder contains resources for training a simple neural network to classify handwritten digits.

It also contains a challenge to use what you know to solve a little bit of a more challenging task, CIFAR-100.

## Setup

To start, you'll need to have python installed (I use [python 3.11](https://www.python.org/downloads/release/python-3119/)).

Create a folder for AI club stuff and open it in VS code.

### 1. Create Virtual Environment
You'll need to create a virtual environment to install your dependencies to. 

In your VS code terminal, run

```bash
pip install virtualenv
```
This installs the tool necessary to create the virtual environment (you'll only need to do this once after installing python, it will install it to the global python environment).

To create the environment, run
```bash
virtualenv venv
```

Run `source ./venv/bin/activate` (on mac) or `./venv/scripts/activate` (on windows) to activate the virtual environment. You should see a (venv) in your terminal

### 2. Install Dependencies

To run any jupyter notebook, you need to install ipython. And you'll need tensorflow, matplotlib, and numpy to run this *particular* notebook:

**(mac)**
```bash
pip install tensorflow matplotlib numpy ipython
```

**(windows)**
```bash
pip install tensorflow-cpu matplotlib numpy ipython
```

### 3. Configure VS Code

After opening the notebook in VS Code, you'll need to select the virtual environment you just created, so that the notebook can run python code.

Above the notebook and to the right (in VS code) you'll see a "Select Kernel" button, click that. Select "Python Environments" and select "venv" (it might also show the path to the venv you just created).

You're all set! To run a cell, hit `ctrl+enter` or click the play button on the left of the cell. To run all the cells, see the tool bar at the top of the page!

### 4. Experiment

After running the notebook, try to tackle the challenges at the bottom. 

Once you feel ready, move on to attempt the CIFAR-100 challenge.

