# csci-4521

This repo is made as a boilerplate/template for classwork in CSCI 4521.

## Setup Instructions

1. **Install Python 3.12 or newer**:

   - Download and install Python from the [official website](https://www.python.org/downloads/).
   - Make sure to check the option to 'Add Python to PATH' during installation. (Don't mess this up man)

2. **Clone the repository and create virtual environment**:
   Skipping the cloning step here, yall got it.

## Create the virtual environment

python -m venv venv

### Activate for Windows

.\venv\Scripts\activate

### Activate for Linux/macOS

source venv/bin/activate

I believe you'll need to activate each time you reset the terminal instance.

## Install dependencies

pip install --upgrade pip
pip install -r requirements.txt

## Jupyter Notebook

This repo has 3 folders you may use as a template for the class.
Exercises, homework and lectures. Homework just has a main.py since it assumes you won't be coding in a notebook environment for those assignments.
Everything else will be in notebook. You can always move things around and just add an .ipynb file to any folder you create.

## Running Jupyter Notebook

jupyter notebook

## Cloning vs. forking

If you plan on pushing your code to Github I recommend you fork this repo, then make it private (for obvious reasons).
Otherwise, cloning should be fine.
