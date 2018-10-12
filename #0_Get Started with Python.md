# Getting Started with Python

To get started with python, you need to download the latest version from Paython from
Python's website https://www.python.org/downloads/

	** Click on `add Python to Path` before you start installation to add this required version to windows

* Here, we’ll give an overview of three ways to run Python code on your computer.
Strongly recommend becoming familiar with both methods.

## 1. Running Python Using Text Editors

### Atom
To run Python code in Atom, please follow the following instructions:

    a) Save the file with the extension (`.py`)

    b) Install (script) package in Atom

    c) To run the code, you can use the keyboard shortcut: `Control + Shift + b`


### Sublime Text
  a) Save the file with the extension (`.py`)
	b) To run the code, you can use the keyboard shortcut: `Control b`

## 2. Running Python Using Command Lines

You can also run Python does using command lines in Windows; the following steps explain it:
    * You need to install Git from https://git-scm.com/download/win
		* Save your file with a `.py` extension.
		* Use the command line to navigate to the directory in which your Python file is saved
		* Run the Python file by typing `winpty python`, followed by the full name of the Python file.


## 3. Running Python Using Miniconda (Jupyter Notebook)


  	* Install [Miniconda](https://conda.io/miniconda.html)
  	* Open Anaconda Prompt and use the following commands [one-time setup]:
  #### To create a new folder (environment)
        conda create --name [folder name]
  #### To activate jupyter notebook
        activate [folder name]
        jupyter notebook

	After you create the folder and activate it, you can open the notebook by just typing `Jupyter Notebook` in Anaconda Prompt
