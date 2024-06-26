# Python for Data Science &amp; Machine Learning 

In this repo you'll learn how to use NumPy, Pandas, Seaborn, Plotly, Scikit-Learn, Machine Learning, Tensorflow, and more!

# Introduction to Anaconda

Anaconda is a popular open-source distribution of Python and R programming languages, specifically designed for scientific computing and data science. We will be using it for data analysis, machine learning, artificial intelligence, and more. 

TLDR; Anaconda simplifies package/env management and deployment, making it an essential tool for data scientists and developers.

# Quick Guide: Installing Anaconda and Setting Up Your First Environment

## Step 1: Download Anaconda

- Visit https://www.anaconda.com/
- Choose the version for your operating system (Windows, macOS, or Linux).

## Step 2: Install Anaconda

- Run the downloaded installer.
- Follow the installation instructions:
  - Next
  - Agree to terms
  - Install for just me
  - Check add Anaconda to my PATH env & Register Anaconda as default (if you want)

## Step 3: Verify Installation

After installation, open a terminal (or Anaconda Prompt on Windows) and run:

```sh
conda --version
```

Or search for 'Anaconda' in your search bar. You should see the Navigator and the terminal. 

![image](https://github.com/jvick1/Python/assets/32043066/04e3b3ea-dd9d-4376-902c-2080d0c7b4a7)

## Step 4: Create Your First Environment

- Open a terminal or Anaconda Prompt.
- Create a new environment named datascience with the necessary packages, let's do numpy first:

```sh
conda create --name datascience numpy
```

- Activate your env

```sh
conda activate datascience
```

- Testing your env - A new browser window should open, allowing you to start working on your data science projects. Just make sure you are in the right working directory. 

```sh
jupyter notebook
```

- Deactivating your env

```sh
conda deactivate
```

# Note:

You can install a different version of Python or multiple packages like so:

```sh
conda create --name datascience python=3.8 numpy pandas scikit-learn jupyter
```

In the Anaconda terminal, `(base)` indicates that you are currently in the default Anaconda environment also known as root, while `(datascience)` shows that you have activated a custom environment named `datascience`. Environments allow you to manage dependencies and packages separately for different projects.

![image](https://github.com/jvick1/Python/assets/32043066/cdaf8d5e-dce0-4df0-80cd-54c5b6fbab33)


