# Installation

Our labs use Jupyter. The recommended way to install it is by installing
Anaconda, an all-in-one distribution that comes with Python, Jupyter, and many
other useful packages.

Download the installers at https://www.anaconda.com/distribution/, and follow
the instructions at https://docs.anaconda.com/anaconda/install/ to set it up.
Choose the latest version of Python.

One thing to note is that we want Anaconda to reside in our home directory.
However, this means that we may needs to add its bin folder to our PATH
variable.

## Installing conda environment

For each lab, we will provide a conda environment to work with that contains
all of the necessary dependencies. You can install it by running:

```
conda env create -f lab1.yml
```

Then, activate your environment by running:

```
conda activate lab1
```

You may also need to specify to Jupyter what environment it should use as the interpreter. To do this in Vscode, press "Crtl+Shift+P" and type in "Jupyter: Select Interpreter to Start Jupyter Server." 

In the drop down menu, select the corresponding environment. Vscode may need to be restarted in order to recognize the newly created environment. 
