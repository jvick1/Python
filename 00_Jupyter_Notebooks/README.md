# Python for Data Science &amp; Machine Learning 

In this repository, I will show you how to open your Anaconda terminal, navigate to your directory, launch Jupyter Notebooks from the command line, and demonstrate some of the basics of using Jupyter Notebooks.

# Anaconda Command Prompt

Launch your Anaconda Command Prompt. 

If you don't have Anaconda installed please finish the `README.md` file in the root folder before starting this repo.

![image](https://github.com/jvick1/Python/assets/32043066/04e3b3ea-dd9d-4376-902c-2080d0c7b4a7)

Key commands include:
- `dir` (Windows) or `ls` (macOS/Linux): Show the contents of the current directory.
- `cd [directory]`: Change the current directory to the specified directory.
- `cd ..`: Move up one directory level.
- `mkdir [directory]`: Create a new directory.
- `conda list`: List all installed packages in the current environment.
- `conda env list`: List all available Conda environments.
- `conda activate [environment]`: Activate the specified Conda environment.
- `conda deactivate`: Deactivate the current Conda environment.
- `jupyter notebook`: Launch Jupyter Notebooks from the command line.

In the example below I change my drive, cd into `E:\Code`, print the directory, cd into `Python`, create a new folder, cd into that, and launch my Jupyter Notebook from there. 

![image](https://github.com/jvick1/Python/assets/32043066/b772292b-5a73-497d-9335-31131fa838f8)

# Creating a new Jupyter Notebook

This will open your notebook in a browser. Chrome or Brave often provide the best compatibility. In the top right of your screen, click to create a new notebook.

![image](https://github.com/jvick1/Python/assets/32043066/cda8d452-ee19-488c-8e63-89c7d178d5f1)

A kernel is an instance of Python that runs your code in a Jupyter Notebook, handling computations and executing code cells.

Once you select your kernel we now have our blank notebook! 

![image](https://github.com/jvick1/Python/assets/32043066/a4dbbc21-7cb4-4e8a-8732-9a7c1f14fcdd)

While here let's rename to something like `intro` you can do so by clicking the untilted text or in your directory. 

![image](https://github.com/jvick1/Python/assets/32043066/5a028927-041d-4689-8038-9aeb76fe1ad8)

# Jupyter Notebook Guide

## Cells

Jupyter Notebooks are organized into cells. There are three main types of cells:

- **Code Cells:** Used to write and execute code. You can run the code by pressing Shift + Enter or clicking the "Run" button.
- **Markdown Cells:** Used for writing formatted text using Markdown syntax. Markdown allows you to include headers, lists, links, images, and more.
- **Raw Cells:** Used for writing raw text that will not be formatted or executed.

## Basic Usage 

- **Create a Cell:** Click on an existing cell and press `A` to add a cell above or `B` for below.
- **Running a Cell:** Click the "Run" button or press `Shift + Enter` to execute code or render Markdown

## Managing the Kernel 

- **Restart Kernel:** Click "Kernel" in the menu and select "Restart". This is useful if your code is not running as expected or if you want to clear all variables.
- **Change Kernel:** Click "Kernel" in the menu and select "Change Kernel" to switch to a different programming language or environment.

## Working with Environments 

Create an Environment:
```sh
conda create --name myenv python=3.8
```
Activate an Environment:
```sh
conda activate myenv
```
Install Packages in an Environment:
```sh
conda install numpy pandas
```

## Using Markdown Cells

- Create a Markdown Cell: Change the cell type to "Markdown" from the dropdown menu or press M while in Command mode (press Esc to enter Command mode).
- Write Markdown:
```markdown
# This is a header
Here is some **bold text** and some *italic text*.
- Bullet point 1
- Bullet point 2
```

# Example 

Now let's try some simple outputs like strings or addition:
![image](https://github.com/jvick1/Python/assets/32043066/cba5a3dc-2a65-4981-8b52-cd643b17c4f7)
